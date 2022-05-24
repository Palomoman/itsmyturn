<template>
  <div class="aboutMe">
    <div class="about-content">
      <article class="aboutCard">
        <img src="../../assets/brain-solid.svg" height="35" />
        <p>{{ Cep1 }}</p>
        <p>{{ Cep2 }}</p>
        <p>{{ Cep3 }}</p>
      </article>
      <article class="aboutCard">
        <img src="../../assets/brain-solid.svg" height="35" />
        <p>{{ Enfocat1 }}</p>
        <p>{{ Enfocat2 }}</p>
        <p>{{ Enfocat3 }}</p>
      </article>
      <article class="aboutCard">
        <img src="../../assets/brain-solid.svg" height="35" />
        <p>{{ UxUi1 }}</p>
        <p>{{ UxUi2 }}</p>
        <p>{{ UxUi3 }}</p>
      </article>
      <article class="aboutCard">
        <img src="../../assets/user-solid.svg" height="35" />
        <p>{{ Yo1 }}</p>
        <p>{{ Yo2 }}</p>
        <p>{{ Yo3 }}</p>
        <p>{{ Yo4 }}</p>
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
      UxUi3: "Autodidact",
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