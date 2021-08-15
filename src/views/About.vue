<template lang="">
  <home-layout>
    <about-banner />
    <details-about-us />
    <faq />
    <our-teams />
  </home-layout>
</template>
<script>
  import HomeLayout from "../components/Layouts/HomeLayout.vue"
  import AboutBanner from '../components/AboutBanner.vue'
  import DetailsAboutUs from '../components/DetailsAboutUs.vue'
  import Faq from '../components/Faq.vue'
  import OurTeams from '../components/OurTeams.vue'
export default {
  components:{
    HomeLayout,
    AboutBanner,
    DetailsAboutUs,
    Faq,
    OurTeams
  }

};
</script>
<style scoped></style>
