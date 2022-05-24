<template>
  <header id="header">
    <nav id="navBar" class="navbar-content">
      <span class="logo">
        <strong style="color: #005781">Guillem</strong> Castaño Medina
      </span>
      <div class="navbar-content">
        <ul class="nav-items">
          <li>
            <div>
              <a class="navbar-link" href="#video">Who am I</a>
            </div>
          </li>
          <li>
            <div>
              <a class="navbar-link" href="#education">About me</a>
            </div>
          </li>
          <li>
            <div>
              <a class="navbar-link" href="#skills">Skills</a>
            </div>
          </li>
          <li>
            <div>
              <a class="navbar-link" href="#contact">Contact</a>
            </div>
          </li>
        </ul>
      </div>
      <!-- <div @click="mostrarMenu()" class="icono-menu">
        <img src="../assets/icono-menu.svg" />
      </div> -->
    </nav>
    <div class="navbar-links-mobile">
      <a class="navbar-link" href="#video">Who am I</a>
      <a class="navbar-link" href="#skills">Education</a>
      <a class="navbar-link" href="#education">Skills</a>
      <a class="navbar-link" href="#contact">Contact</a>
    </div>
    <!--LIMPIAR FLOTADOS-->
    <div class="clearfix"></div>
  </header>
</template>

<script>
export default {
  name: "NavBar",
  // created() {
  //   document.addEventListener("scroll", this.handleScroll);
  // },
  // unmounted() {
  //   document.addEventListener("scroll", this.handleScroll);
  // },
  methods: {
    // handleScroll() {
    //   console.log("hay scroll");
    //   document.querySelector(".navbar-sticky").style.display = "flex";
    // },
    mostrarMenu() {
      let menuMobil = document.querySelector(".navbar-links-mobile");
      let menuLeft = menuMobil.offsetLeft;

      if (menuLeft > 0) {
        menuMobil.style.left = 0;
      } else {
        menuMobil.style.left = "100vw";
      }
    },
  },
};
</script>
