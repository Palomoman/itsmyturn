<template>
  <div class="container">
    <TarjetaTexto></TarjetaTexto>
    <TarjetaImagen></TarjetaImagen>
  </div>
</template>
<script>
import TarjetaTexto from "./TarjetaTexto.vue";
import TarjetaImagen from "./TarjetaImagen.vue";
export default {
  name: "ContentComponentInverse",
  components: { TarjetaTexto, TarjetaImagen },
};
</script>

<style>
@import "../assets/css/content.css";
</style>