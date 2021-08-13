<template>
  <home-layout>
    <div class="home">
      <carousel />
    </div>
  </home-layout>
</template>

<script>
// @ is an alias to /src
import HomeLayout from "../components/Layouts/HomeLayout.vue";
import Carousel from '../components/Carousel.vue';

export default {
  name: "Home",
  components: {
    HomeLayout,
    Carousel,
  },
};
</script>
