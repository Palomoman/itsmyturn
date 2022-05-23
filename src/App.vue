<template>
  <div>
    <div class="first-half">
      <NavBar></NavBar>
      <BienvenidaComponent></BienvenidaComponent>
    </div>
    <div class="second-half">
      <div>
        <VideoComp></VideoComp>
        <EducationComponent></EducationComponent>
        <SkillsComponent></SkillsComponent>
        <ContactComponent></ContactComponent>
        <FooterComponent></FooterComponent>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import BienvenidaComponent from "./components/BienvenidaComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";
import EducationComponent from "./components/EducationComponent.vue";
import SkillsComponent from "./components/SkillsComponent.vue";
import ContactComponent from "./components/ContactComponent.vue";
import VideoComp from "./components/VideoComp.vue";

export default {
  name: "App",
  components: {
    NavBar,
    BienvenidaComponent,
    FooterComponent,
    EducationComponent,
    SkillsComponent,
    ContactComponent,
    VideoComp,
  },
};
</script>

<style>
@import "./assets/css/navBar-styles.css";
@import "./assets/css/first-half-styles.css";
@import "./assets/css/second-half-styles.css";
@import "./assets/css/bienvenida.css";
@import "./assets/css/footer.css";
</style>
