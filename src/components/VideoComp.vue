<template>
  <video id="video" autobuffer controls autoplay class="video">
    <source id="mp4" src="../assets/WhoamI.mp4" type="video/mp4" />
  </video>
</template>

<script>
export default {
  name: "VideoComp",
};
</script>

<style>
@import "../assets/css/video.css";
</style>