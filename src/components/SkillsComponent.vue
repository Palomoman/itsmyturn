<template>
  <article id="title">Skills</article>
  <div id="skills" class="container">
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