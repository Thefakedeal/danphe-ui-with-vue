<template lang="">
   <section class="main-topic py-3">
        <div class="container">
            <div class="list d-flex justify-content-center align-items-center">
                <div class="box">
                    <a href="#">Test Preparation</a>
                </div>
                <div class="box">
                    <a href="#">Visa Counseling</a>
                </div>
                <div class="box">
                    <a href="#">Book Appointment</a>
                </div>
                <div class="box">
                    <a href="#">Event Registration</a>
                </div>
                <div class="box">
                    <a href="#">Career Counseling</a>
                </div>
            </div>
        </div>
    </section>
</template>
<script>
export default {
    
}
</script>
<style scoped>
  .main-topic .container .list {
  -ms-flex-wrap: wrap;
      flex-wrap: wrap;
}

.main-topic .container .list .box {
  background-color: #1F2B33;
  padding: 7px 13px;
  margin: 7px;
  border-radius: 5px;
}

.main-topic .container .list .box:hover {
  -webkit-box-shadow: 1px 1px 10px #1F2B33;
          box-shadow: 1px 1px 10px #1F2B33;
}

.main-topic .container .list .box a {
  text-decoration: none;
  color: #ffffff;
}  
</style>