<template>
  <div>
    <div class="first-half">
      <NavBar></NavBar>
      <BienvenidaComponent></BienvenidaComponent>
    </div>
    <div class="second-half">
      <div>
        <ContentComponent></ContentComponent>
        <ContentComponentInverse></ContentComponentInverse>
        <ContentComponent></ContentComponent>
        <FooterComponent></FooterComponent>
      </div>
    </div>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import BienvenidaComponent from "./components/BienvenidaComponent.vue";
import FooterComponent from "./components/FooterComponent.vue";
import ContentComponent from "./components/ContentComponent.vue";
import ContentComponentInverse from "./components/ContentComponentInverse.vue";
export default {
  name: "App",
  components: {
    NavBar,
    BienvenidaComponent,
    FooterComponent,
    ContentComponent,
    ContentComponentInverse,
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
