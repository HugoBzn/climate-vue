<script setup>
import Formulario from "./components/Formulario.vue";

import useClima from "./composables/useClima";

const { obtenerClima } = useClima();
</script>

<template>
  <header>
    <h1 class="titulo">Buscador de Clima</h1>
  </header>

  <div class="contenedor buscador-clima">
    <Formulario @obtener-clima="obtenerClima" />
  </div>
</template>
