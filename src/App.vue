<template>
  <h1>My Sylhet Tour</h1>
  <h3>Presenting in Carousel By Vue + Vite</h3>
  <carousel :slides="slides" :interval="3000" controls indicators></carousel>
</template>

<script>
import Carousel from "./components/carousel/Carousel.vue";

export default {
  name: "App",
  components: { Carousel },
  data: () => ({
    slides: [
      "https://raw.githubusercontent.com/SalmanFarcy78/vue-carousel/master/2.jpg",
      "https://raw.githubusercontent.com/SalmanFarcy78/vue-carousel/master/3.jpg", 
      "https://raw.githubusercontent.com/SalmanFarcy78/vue-carousel/master/4.jpg",
      "https://raw.githubusercontent.com/SalmanFarcy78/vue-carousel/master/1.jpg",
      "https://raw.githubusercontent.com/SalmanFarcy78/vue-carousel/master/7.jpg",
    ],
  }),
};
</script>

<style></style>