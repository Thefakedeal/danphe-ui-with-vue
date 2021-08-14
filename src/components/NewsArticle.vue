<template lang="">
  <div class="card mb-3">
    <div class="d-sm-flex item">
      <div class="image">
        <a href="#">
          <img :src="article.image" alt="" />
        </a>
      </div>
      <div class="content">
        <a :href="article.link">
          {{ article.title }}
        </a>
        <p>
          <i class="far fa-calendar-alt"></i>
          <span>{{ article.date }}</span>
        </p>
        <div class="text">
          <span>
            {{ article.description }}
          </span>
        </div>
        <div class="my-2 read">
          <a :href="article.link" class="dark-btn">Read More</a>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  props: {
    article: Object,
  },
};
</script>
<style scoped>
.card .item .image img {
  width: 200px;
  height: 100%;
  -o-object-fit: cover;
  object-fit: cover;
}

.card .item .content {
  padding-left: 10px;
}

.card .item .content a {
  text-decoration: none;
  font-size: 20px;
  font-weight: 700;
  color: #1f2b33;
}

.card .item .content a:hover {
  color: seagreen;
}

.card .item .content p {
  margin-bottom: 1px;
}

.card .item .content p span {
  color: #a8a5a5;
}

.card .item .content .text {
  font-size: 14px;
}

.card .item .content .read .dark-btn {
  text-decoration: none;
  color: white;
  background-color: #1f2b33;
  padding: 5px 7px;
  border: none;
  font-size: 14px;
  border-radius: 5px;
  font-weight: 500;
}

.card .item .content .read .dark-btn:hover {
  background-color: #ebedee;
  color: #1f2b33;
}

@media screen and (max-width: 500px) {
  .card .item .image img {
    width: 100%;
  }
}
</style>
