<template>
  <div id="education" class="container">
    <TarjetaImagen></TarjetaImagen>
    <TarjetaTexto></TarjetaTexto>
  </div>
</template>
<script>
import TarjetaImagen from "../components/Tarjetas/TarjetaImagen.vue";
import TarjetaTexto from "../components/Tarjetas/TarjetaTexto.vue";

export default {
  name: "EducationComponent",
  components: { TarjetaTexto, TarjetaImagen },
};
</script>

<style>
@import "../assets/css/content.css";
</style>