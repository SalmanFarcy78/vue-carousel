<template>
  <h1 style = "text-align: center; color: green; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;"> My Tour Album in Carousel By Vue + Vite </h1>
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