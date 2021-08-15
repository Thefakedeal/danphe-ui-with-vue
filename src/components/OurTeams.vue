<template lang="">
    <section>
        <h2 class="text-center"> Our Teams </h2>
        <div class="row p-2 gy-5">
            <div class="col-lg-3 col-md-4 col-6" v-for="team in teams" :key="team.name">
                <el-card :body-style="{ padding: '2px' }">
                    <div :style="{ backgroundImage: `url(${team.image})`}" class="image"> </div>
                    <div style="padding: 14px;">
                        <div> <b>{{team.name}}</b> </div>
                        <small class="text-muted">{{team.position}}</small>
                        <div class="py-1"> {{ team.address }} </div>
                    </div>
                </el-card>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    data(){
        return {
            teams: [
                {
                    name: 'Employee 1',
                    position: 'CEO',
                    address: 'Dharan-7',
                    image: 'https://source.unsplash.com/random',
                },
                {
                    name: 'Employee 2',
                    position: 'Reception',
                    address: 'Dharan-8',
                    image: 'https://source.unsplash.com/random',
                },
                {
                    name: 'Employee 3',
                    position: 'Teacher',
                    address: 'Dharan-8',
                    image: 'https://source.unsplash.com/random',
                },
                {
                    name: 'Employee 4',
                    position: 'Teacher',
                    address: 'Dharan-7',
                    image: 'https://source.unsplash.com/random',
                },
                {
                    name: 'Employee 5',
                    position: 'Technician',
                    address: 'Dharan-5',
                    image: 'https://source.unsplash.com/random',
                },
            ]
        }
    }
}
</script>
<style scoped>
   .image{
       background-position: center;
       background-size: cover;
       padding-top: 50%;
   } 
</style>