<template>
  <div class="aboutMe">
    <div class="about-content">
      <article class="aboutCard">
        <h4>{{ Cep1 }}</h4>
        <h5>{{ Cep2 }}</h5>
        <h5>{{ Cep3 }}</h5>
      </article>
      <article class="aboutCard">
        <h4>{{ Enfocat1 }}</h4>
        <h5>{{ Enfocat2 }}</h5>
        <h5>{{ Enfocat3 }}</h5>
      </article>
      <article class="aboutCard">
        <h4>{{ UxUi1 }}</h4>
        <h5>{{ UxUi2 }}</h5>
        <h5>{{ UxUi3 }}</h5>
      </article>
      <article class="aboutCard">
        <h4>{{ Yo1 }}</h4>
        <h4>{{ Yo2 }}</h4>
        <h5>{{ Yo3 }}</h5>
        <h5>{{ Yo4 }}</h5>
      </article>
    </div>
  </div>
</template>

<script>
export default {
  name: "TarjetaTextoEducation",
  data() {
    return {
      UxUi1: "Graphic Design",
      UxUi2: "UX/UI",
      Cep1: "Web Application development",
      Cep2: "Certificate of Higher Education",
      Cep3: "Centre d'Estudis Politècnics",
      Enfocat1: "Java, Sql and web development Bootcamp",
      Enfocat2: "IT Bootcamp",
      Enfocat3: "Fundació Esplai IT School",
      Yo1: "Multidisciplinar Artist",
      Yo2: "Music",
      Yo3: "Novels",
      Yo4: "Videogames and strategy games",
    };
  },
};
</script>

<style>
@import "../../assets/css/educationText.css";
</style>