<template>
  <div class="alerta">
    <slot></slot>
  </div>
</template>

<style scoped>
.alerta {
  text-align: center;
  margin-bottom: 2rem;
  color: var(--blanco);
  text-transform: uppercase;
  font-weight: 900;
  font-size: 1.8rem;
  padding: 0.5rem;
  background: rgba(255, 0, 0, 0.300);
  border-radius: 1rem;
}
</style>
