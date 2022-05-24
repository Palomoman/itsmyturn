<template>
  <div class="contact-container">
    <div class="CV">
      <a
        class="btn btn-white btn-animate"
        href="/public/cv/GuillemCastañoMedinaCV.pdf"
        download
        alt="Botón para descargar mi currículo"
        >Download my CV</a
      >
    </div>
    <div class="icons">
      <a href="https://www.linkedin.com/in/guillemcasta%C3%B1omedina/">
        <img
          alt="icono de linkedin. Link que te lleva a mi página de linked in."
          src="../../assets/linkedin-brands.svg"
          width="150"
          height="70"
        />
      </a>
      <a href="https://github.com/Palomoman">
        <img
          alt="icono de github. Link que te lleva a mi página de git hub."
          src="../../assets/github-brands.svg"
          width="150"
          height="70"
        />
      </a>
    </div>
  </div>
</template>

<script>
export default {
  name: "TarjetaTextoContact",
};
</script>

<style>
@import "../../assets/css/ContactTextComponent.css";
</style>