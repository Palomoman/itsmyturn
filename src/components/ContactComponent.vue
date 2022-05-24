<template>
  <div id="contact" class="container">
    <TarjetaImagenContact></TarjetaImagenContact>
    <TarjetaTextoContact></TarjetaTextoContact>
  </div>
</template>
<script>
import TarjetaImagenContact from "./Tarjetas/TarjetaImagenContact.vue";
import TarjetaTextoContact from "./Tarjetas/TarjetaTextoContact.vue";

export default {
  name: "ContactComponent",
  components: { TarjetaTextoContact, TarjetaImagenContact },
};
</script>

<style>
@import "../assets/css/content.css";
@import "../assets/css/contact.css";
</style>