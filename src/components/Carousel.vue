<template lang="">
  <el-carousel :interval="5000" arrow="always" >
    <el-carousel-item v-for="(image, index) in images" :key="index">
      <img :src="image" class="w-100" alt=""/>
    </el-carousel-item>
  </el-carousel>
</template>
<script>
export default {
  data() {
    return {
      images: [
          "https://picsum.photos/1350/480",
          "https://picsum.photos/1350/480",
          "https://picsum.photos/1350/480",
      ]
    };
  },
};
</script>
<style lang="scss" scoped>

img{
    height: 500px;
    object-fit: cover;
    object-position: center;
}
@media only screen and (max-width: 768px) {
  img {
    height: 250px;
  }
  h1 {
    font-size: 2rem;
  }
  p {
    font-size: 14px;
  }
}

@media only screen and (max-width: 500px) {
  h1 {
    font-size: 1.2rem;
  }
  p {
    font-size: 11px;
  }
}
</style>
