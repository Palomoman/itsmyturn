<template>
  <header>
    <!-- LOGO -->
    <!-- <img src="../assets/logo.png" class="logo" alt="Logotipo" /> -->
    <span class="logo">
      <strong style="color: #005781">Guillem</strong> Castaño Medina
    </span>

    <!-- MENU -->
    <nav>
      <ul class="nav-items">
        <li>
          <router-link to="/" active-class="active">Main</router-link>
        </li>
        <li>
          <router-link to="/education" active-class="active"
            >Education</router-link
          >
        </li>
        <li>
          <router-link to="/skills" active-class="active">Skills</router-link>
        </li>
        <li>
          <router-link to="/contact" active-class="active">Contact</router-link>
        </li>
      </ul>
    </nav>

    <!--LIMPIAR FLOTADOS-->
    <div class="clearfix"></div>
  </header>
</template>

<script>
export default {
  name: "NavBar",
};
</script>