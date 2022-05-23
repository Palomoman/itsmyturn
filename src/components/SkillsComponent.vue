<template>
  <div class="container">
    <TarjetaTexto></TarjetaTexto>
    <TarjetaImagen></TarjetaImagen>
  </div>
</template>
<script>
import TarjetaImagen from "../components/Tarjetas/TarjetaImagen.vue";
import TarjetaTexto from "../components/Tarjetas/TarjetaTexto.vue";

export default {
  name: "SkillsComponent",
  components: { TarjetaTexto, TarjetaImagen },
};
</script>

<style>
@import "../assets/css/content.css";
</style>