<template>
  <div id="contact" class="container">
    <TarjetaImagen></TarjetaImagen>
    <TarjetaTexto></TarjetaTexto>
  </div>
</template>
<script>
import TarjetaImagen from "./Tarjetas/TarjetaImagen.vue";
import TarjetaTexto from "./Tarjetas/TarjetaTexto.vue";

export default {
  name: "ContactComponent",
  components: { TarjetaTexto, TarjetaImagen },
};
</script>

<style>
@import "../assets/css/content.css";
@import "../assets/css/contact.css";
</style>