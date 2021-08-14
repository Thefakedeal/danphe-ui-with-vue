<template lang="">
   <section class="testimonial py-5">
        <div class="container">
            <div class="row">
                <div class="col-md-7 mx-auto text-center">
                    <button class="btn btn-sm btn-danger">Testimonial</button>
                    <h1 class="fs-3 fw-bold mt-3">Trusted and Loved One</h1>
                    <hr class="w-50 mx-auto">
                </div>
            </div>
            <el-carousel :interval="4000" type="card" >
                <el-carousel-item v-for="testimonial in testimonials" :key="testimonial.id">
                    <testimonial-card :testimonial="testimonial" />
                </el-carousel-item>
            </el-carousel>
        </div>
    </section>
</template>
<script>
import TestimonialCard from './TestimonialCard.vue';
export default {
    components:{
        TestimonialCard
    },
    data(){
        return {
            testimonials:[
                {
                    id: Math.random(),
                    name: "NAAST Multiple Campus",
                    image: "https://source.unsplash.com/random",
                    address: "Dharan",
                    description: `Lorem ipsum, dolor sit amet
                    consectetur adipisicing elit. Accusantium,
                    ea? Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Voluptatum, cumque aliquid alias sunt nemo,
                    suscipit deleniti deserunt fugiat est sequi id`,
                },
                {
                    id: Math.random(),
                    name: "NAAST Multiple Campus",
                    image: "https://source.unsplash.com/random",
                    address: "Dharan",
                    description: `Lorem ipsum, dolor sit amet
                    consectetur adipisicing elit. Accusantium,
                    ea? Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Voluptatum, cumque aliquid alias sunt nemo,
                    suscipit deleniti deserunt fugiat est sequi id`,
                },
                {
                    id: Math.random(),
                    name: "NAAST Multiple Campus",
                    image: "https://source.unsplash.com/random",
                    address: "Dharan",
                    description: `Lorem ipsum, dolor sit amet
                    consectetur adipisicing elit. Accusantium,
                    ea? Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Voluptatum, cumque aliquid alias sunt nemo,
                    suscipit deleniti deserunt fugiat est sequi id`,
                },
                {
                    id: Math.random(),
                    name: "NAAST Multiple Campus",
                    image: "https://source.unsplash.com/random",
                    address: "Dharan",
                    description: `Lorem ipsum, dolor sit amet
                    consectetur adipisicing elit. Accusantium,
                    ea? Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Voluptatum, cumque aliquid alias sunt nemo,
                    suscipit deleniti deserunt fugiat est sequi id`,
                },
                {
                    id: Math.random(),
                    name: "NAAST Multiple Campus",
                    image: "https://source.unsplash.com/random",
                    address: "Dharan",
                    description: `Lorem ipsum, dolor sit amet
                    consectetur adipisicing elit. Accusantium,
                    ea? Lorem ipsum dolor sit amet, consectetur adipisicing elit.
                    Voluptatum, cumque aliquid alias sunt nemo,
                    suscipit deleniti deserunt fugiat est sequi id`,
                },
            ]
        }
    }
}
</script>
<style scoped>
 
</style>