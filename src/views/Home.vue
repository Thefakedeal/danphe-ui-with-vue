<template>
  <home-layout>
    <div class="home">
      <carousel />
      <main-topic-links />
      <this-is-us />
      <aboout-section />
      <latest-news />
      <testimonial />
      <join-now />
      <contacts />
      <home-map />
    </div>
  </home-layout>
</template>

<script>
// @ is an alias to /src
import HomeLayout from "../components/Layouts/HomeLayout.vue";
import Carousel from '../components/Carousel.vue';
import MainTopicLinks from '../components/MainTopicLinks.vue';
import ThisIsUs from '../components/ThisIsUs.vue';
import AbooutSection from '../components/AbooutSection.vue';
import LatestNews from '../components/LatestNews.vue';
import Testimonial from '../components/Testimonial.vue';
import JoinNow from '../components/JoinNow.vue'
import Contacts from '../components/Contacts.vue';
import HomeMap from '../components/HomeMap.vue';
export default {
  name: "Home",
  components: {
    HomeLayout,
    Carousel,
    MainTopicLinks,
    ThisIsUs,
    AbooutSection,
    LatestNews,
    Testimonial,
    JoinNow,
    Contacts,
    HomeMap
  },
};
</script>