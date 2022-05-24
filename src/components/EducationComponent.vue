<template>
  <article id="education" class="title">About me</article>
  <div class="container">
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