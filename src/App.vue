<template>
  <Basic />
  <hr>
  <Autoplay />
  <hr>
  <Reactivity />
  <hr>
  <DynamicSlides />
  <hr>
  <Thumbnails />
  <hr>
  <Video />
</template>

<script setup lang="ts">
import Autoplay from './components/Autoplay.vue';
import Basic from './components/Basic.vue';
import DynamicSlides from './components/DynamicSlide.vue';
import Reactivity from './components/Reactivity.vue';
import Thumbnails from './components/Thumbnails.vue';
import Video from './components/Video.vue';
import '@splidejs/vue-splide/css';
</script>

<style>
body {
  font-family: 'Poppins', sans-serif;
  padding: 5rem 0;
}
h1 {
  text-align: center;
}
hr {
  width: 200px;
  max-width: 50%;
  margin: 4rem auto;
}
button {
  font-family: inherit;
}
.wrapper {
  max-width: 600px;
  margin: 0 auto;
}
.splide__slide {
  background: #eee;
}
.splide__slide img {
  width: 100%;
  height: 100%;
  object-fit: cover;
}
.splide--nav {
  margin-top: 1rem;
}
</style>
