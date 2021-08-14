<template lang="en">
    <section class="address py-5">
        <div class="container">
            <div class="row">
                <div class="col">
                    <div class="contact d-flex justify-content-between align-items-center text-white">
                        <div class="box text-center text-white">
                            <div class="icon">
                                <i class="fas fa-map-marker-alt"></i>
                            </div>
                            <h5>Address</h5>
                            <p class="text-white">Itahari, Sunsari</p>
                            <span>Nepal</span>
                        </div>
                        <div class="divide"></div>
                        <div class="box text-center text-white">
                            <div class="icon">
                                <i class="fas fa-phone-alt"></i>
                            </div>
                            <h5>Phone</h5>
                            <p class="text-white">+977-9804090266</p>
                        </div>
                        <div class="divide"></div>
                        <div class="box text-center text-white">
                            <div class="icon">
                                <i class="far fa-envelope"></i>
                            </div>
                            <h5>Email Address</h5>
                            <p class="text-white">itahari@gmail.com</p>
                            <span>danphe@.com</span>
                        </div>
                    </div>
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
section.address .container .row .col .contact {
  background-color: #1F2B33;
  -ms-flex-wrap: wrap;
      flex-wrap: wrap;
  border-radius: 5px;
}

section.address .container .row .col .contact .box {
  width: 300px;
  height: 140px;
  padding: 10px;
  margin: auto;
}

section.address .container .row .col .contact .box .icon {
  width: 40px;
  height: 40px;
  background: #2a373f;
  line-height: 40px;
  margin: 5px auto;
  border-radius: 50%;
  color: #969091;
}

section.address .container .row .col .contact .box h5 {
  font-size: 18px;
}

section.address .container .row .col .contact .box p, section.address .container .row .col .contact .box span {
  margin: 0 0;
  line-height: 15px;
  font-size: 14px;
}

section.address .container .row .col .contact .divide {
  margin: 5px auto;
  width: 1px;
  height: 80px;
  background-color: #ffffff;
  position: relative;
}

section.address .container .row .col .contact .divide::before {
  content: "";
  position: absolute;
  top: 50%;
  -webkit-transform: translateY(-50%);
          transform: translateY(-50%);
  left: -5px;
  width: 2px;
  height: 50px;
  background-color: #ffffff;
}

section.address .container .row .col .contact .divide::after {
  content: "";
  position: absolute;
  top: 50%;
  -webkit-transform: translateY(-50%);
          transform: translateY(-50%);
  right: -5px;
  width: 2px;
  height: 50px;
  background-color: #ffffff;
}

@media screen and (max-width: 992px) {
  section.address .container .row .col .contact .divide {
    display: none;
  }
}

@media screen and (max-width: 500px) {
  section.address .container .row .col .contact .divide {
    display: block;
    width: 80px;
    height: 1px;
    background-color: #ffffff;
    position: relative;
  }
  section.address .container .row .col .contact .divide::before {
    content: "";
    position: absolute;
    left: 50%;
    -webkit-transform: translatex(-50%);
            transform: translatex(-50%);
    top: -5px;
    width: 50px;
    height: 2px;
    background-color: #ffffff;
  }
  section.address .container .row .col .contact .divide::after {
    content: "";
    position: absolute;
    left: 50%;
    -webkit-transform: translatex(-50%);
            transform: translatex(-50%);
    top: 4px;
    width: 50px;
    height: 2px;
    background-color: #ffffff;
  }
}
</style>