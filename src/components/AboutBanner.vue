<template lang="">
       <section class="about banner py-5">
        <div class="container">
            <div class="row">
                <div class="col text-center">
                    <h2 class="fw-bold text-white">About Us</h2>
                    <a href="/" @click.prevent="$router.push({name:'Home'})">Home</a> <span class="text-white">/</span>  <a href="/about" @click.prevent="$router.push({name:'About'})" class="text-decoration-none text-white">About Us</a>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style lang="scss" scoped>
.about {
  background: linear-gradient(rgba(0, 0, 0, 0.562), rgba(0, 0, 0, 0.274)), url('https://picsum.photos/1900/300') no-repeat;
  background-size: cover;
}
</style>