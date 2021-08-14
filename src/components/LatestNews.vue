<template lang="">
  <section class="latest-news py-3">
    <div class="container">
      <div class="row title">
        <div class="col-md-8 mx-auto text">
          <div class="text-center">
            <h1 class="h3 mb-0">Our Latest News</h1>
          </div>
          <hr class="mx-auto mt-1" />
        </div>
      </div>
      <div class="row news-section">
        <div class="col-md-4 facebook d-none d-md-block">
          <iframe
            src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FDanpheEducation&tabs=timeline&width=340&height=500&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId"
            scrolling="no"
            frameborder="0"
            allowfullscreen="true"
            allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
          ></iframe>
        </div>
        <div class="col-md-8 news">
          <div class="text-end">
            <a href="#" class="mb-1 btn btn-sm btn-dark">View All</a>
          </div>
          <news-article v-for="article in articles" :key="article.id" :article="article"/>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
import NewsArticle from "./NewsArticle.vue";
export default {
  components: {
    NewsArticle,
  },
  data() {
    return {
      articles: [
        {
          id: Math.random(),
          title: "Heading News",
          image: "https://picsum.photos/300/200",
          date: "Thrusday, 25 March 2021",
          description: `Lorem ipsum, dolor sit amet
          consectetur adipisicing elit. Accusantium,
          ea? Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          Voluptatum, cumque aliquid alias sunt nemo,
          suscipit deleniti deserunt fugiat est sequi id`,
        },
        {
          id: Math.random(),
          title: "Heading News",
          image: "https://picsum.photos/300/200",
          date: "Thrusday, 25 March 2021",
          description: `Lorem ipsum, dolor sit amet
          consectetur adipisicing elit. Accusantium,
          ea? Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          Voluptatum, cumque aliquid alias sunt nemo,
          suscipit deleniti deserunt fugiat est sequi id`,
        },
        {
          id: Math.random(),
          title: "Heading News",
          image: "https://picsum.photos/300/200",
          date: "Thrusday, 25 March 2021",
          description: `Lorem ipsum, dolor sit amet
          consectetur adipisicing elit. Accusantium,
          ea? Lorem ipsum dolor sit amet, consectetur adipisicing elit.
          Voluptatum, cumque aliquid alias sunt nemo,
          suscipit deleniti deserunt fugiat est sequi id`,
        },
      ],
    };
  },
};
</script>
<style scoped>
.latest-news .container .title .text hr {
  width: 80px;
  height: 2px;
  background-color: #140b0b;
}

.latest-news .container .news-section .facebook {
  margin-top: 35px;
  height: 600px;
}

.latest-news .container .news-section .facebook iframe {
  width: 100%;
  height: 600px;
}
</style>
