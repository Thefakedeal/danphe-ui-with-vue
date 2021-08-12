<template>
  <home-layout>
    <div class="home">
      <img alt="Vue logo" src="../assets/logo.png" />
      <HelloWorld msg="Welcome to Your Vue.js App" />
    </div>
  </home-layout>
</template>

<script>
// @ is an alias to /src
import HelloWorld from "@/components/HelloWorld.vue";
import HomeLayout from "../components/Layouts/HomeLayout.vue";

export default {
  name: "Home",
  components: {
    HelloWorld,
    HomeLayout,
  },
};
</script>
