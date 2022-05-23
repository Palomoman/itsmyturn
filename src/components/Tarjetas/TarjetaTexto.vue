<template>
  <h3>{{ texto1 }}</h3>
  <h4>{{ texto2 }}</h4>
  <h4>{{ texto3 }}</h4>
</template>

<script>
export default {
  name: "TarjetaTexto",
  data() {
    return {
      texto1: "bla bla bla bla bla",
      texto2: "bli bli bli bli",
      texto3: "blo blo blo blo",
    };
  },
};
</script>