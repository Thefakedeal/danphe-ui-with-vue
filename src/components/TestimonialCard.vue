<template lang="">
  <el-card :body-style="{ padding: '0px' }">
       <div class="container-fluid">
            <img :src="testimonial.image" class="image img-fluid">
      <div style="padding: 14px;">
        <span>{{testimonial.name}} - {{testimonial.address}}</span>
        <div class="bottom clearfix">
            <p>
                {{ testimonial.description }}
            </p>
        </div>
      </div>
           </div>
    </el-card>
</template>
<script>
export default {
  props: {
    testimonial: Object,
  },
};
</script>
<style scoped>
     .image {
        object-fit: cover;
        width: 100%;
        height: 200px;
        /* display: block; */
    }
   .bottom {
    margin-top: 13px;
    line-height: 12px;
  }
</style>
