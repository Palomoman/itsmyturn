<template>
  <article id="skills" class="title">Skills</article>
  <div class="container">
    <TarjetaTextoSkills></TarjetaTextoSkills>
    <TarjetaImagenSkills></TarjetaImagenSkills>
  </div>
</template>
<script>
import TarjetaImagenSkills from "./Tarjetas/TarjetaImagenSkills.vue";
import TarjetaTextoSkills from "./Tarjetas/TarjetaTextoSkills.vue";

export default {
  name: "SkillsComponent",
  components: { TarjetaTextoSkills, TarjetaImagenSkills },
};
</script>

<style>
@import "../assets/css/content.css";
</style>