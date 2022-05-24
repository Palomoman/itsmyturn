<template>
  <article id="title">About me</article>
  <div id="education" class="container">
    <TarjetaImagenEducation></TarjetaImagenEducation>
    <TarjetaTextoEducation></TarjetaTextoEducation>
  </div>
</template>
<script>
import TarjetaTextoEducation from "./Tarjetas/TarjetaTextoEducation.vue";
import TarjetaImagenEducation from "./Tarjetas/TarjetaImagenEducation.vue";

export default {
  name: "EducationComponent",
  components: { TarjetaTextoEducation, TarjetaImagenEducation },
};
</script>

<style>
@import "../assets/css/content.css";
</style>