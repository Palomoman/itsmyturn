<template>
  <div class="container">
    <TarjetaImagen></TarjetaImagen>
    <TarjetaTexto></TarjetaTexto>
  </div>
</template>
<script>
import TarjetaTexto from "./TarjetaTexto.vue";
import TarjetaImagen from "./TarjetaImagen.vue";
export default {
  name: "ContentComponent",
  components: { TarjetaTexto, TarjetaImagen },
};
</script>

<style>
@import "../assets/css/content.css";
</style>