<template lang="">
  <footer class="bg-dark text-white py-3">
    <div class="container">
      <div class="row">
        <div class="col-md-6 col-lg-3 course">
          <h5>Course</h5>
          <ul class="list-unstyled">
            <li>
              <a href="#" class="text-decoration-none">
                <i class="fas fa-link"></i> IELTS
              </a>
            </li>
            <li>
              <a href="#" class="text-decoration-none">
                <i class="fas fa-link"></i> GRE
              </a>
            </li>
            <li>
              <a href="#" class="text-decoration-none">
                <i class="fas fa-link"></i> TOEFL
              </a>
            </li>
            <li>
              <a href="#" class="text-decoration-none">
                <i class="fas fa-link"></i> SAT
              </a>
            </li>
            <li>
              <a href="#" class="text-decoration-none">
                <i class="fas fa-link"></i> GMAT
              </a>
            </li>
            <li>
              <a href="#" class="text-decoration-none">
                <i class="fas fa-link"></i> NAT
              </a>
            </li>
          </ul>
        </div>
        <div class="col-md-6 col-lg-3 news">
          <h5>News & Update</h5>
          <a href="#" class="text-decoration-none text-white">
            <div class="item d-flex justify-content-start align-items-center">
              <div class="imgbx">
                <img src="https://source.unsplash.com/random" alt="" />
              </div>
              <div class="content">
                <p class="text-muted">Event Title</p>
                <span>Mar-21,2021</span>
              </div>
            </div>
          </a>
          <a href="#" class="text-decoration-none text-white">
            <div class="item d-flex justify-content-start align-items-center">
              <div class="imgbx">
                <img src="https://source.unsplash.com/random" alt="" />
              </div>
              <div class="content">
                <p class="text-muted">Event Title</p>
                <span>Mar-21,2021</span>
              </div>
            </div>
          </a>
          <a href="#" class="text-decoration-none text-white">
            <div class="item d-flex justify-content-start align-items-center">
              <div class="imgbx">
                <img src="https://source.unsplash.com/random" alt="" />
              </div>
              <div class="content">
                <p class="text-muted">Event Title</p>
                <span>Mar-21,2021</span>
              </div>
            </div>
          </a>
        </div>
        <div class="col-md-6 col-lg-3 contact">
          <h5>Contact Info</h5>
          <div class="d-flex justify-content-start align-items-center item">
            <div class="icon">
              <i class="fas fa-home"></i>
            </div>
            <div class="content">
              <p class="">Office</p>
              <a href="#" class="text-decoration-none text-muted">
                <span>Itahari, Nepal</span>
              </a>
            </div>
          </div>
          <div class="d-flex justify-content-start align-items-center item">
            <div class="icon">
              <i class="fas fa-phone-volume"></i>
            </div>
            <div class="content">
              <p class="">Call Us</p>
              <a href="#" class="text-decoration-none text-muted">
                <span>+9779804090266</span>
              </a>
              <a href="#" class="text-decoration-none text-muted">
                <span>+9779810539469</span>
              </a>
            </div>
          </div>
          <div class="d-flex justify-content-start align-items-center item">
            <div class="icon">
              <i class="fas fa-envelope-square"></i>
            </div>
            <div class="content">
              <p class="">Email Us</p>
              <a href="#" class="text-decoration-none text-muted">
                <span>danphe@gmail.com</span>
              </a>
            </div>
          </div>
        </div>
        <div class="col-md-6 col-lg-3 facebook">
          <h5>Facebook</h5>
          <iframe
            src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2FDanpheEducation&tabs=timeline&width=340&height=500&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true&appId"
            scrolling="no"
            frameborder="0"
            allowfullscreen="true"
            allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
          ></iframe>
        </div>
      </div>
    </div>
  </footer>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
footer .container .row .course ul > li > a {
  color: #ffffff;
  font-size: 14px;
}

footer .container .row .course ul > li > a:hover {
  color: #45acb0;
}

footer .container .row .news .item {
  margin: 10px 0;
}

footer .container .row .news .item:hover {
  background-color: #26343d;
}

footer .container .row .news .item .imgbx img {
  width: 50px;
  height: 50px;
  -o-object-fit: cover;
  object-fit: cover;
}

footer .container .row .news .item .content {
  padding-left: 10px;
}

footer .container .row .news .item .content p {
  margin: 0;
}

footer .container .row .news .item .content span {
  font-size: 11px;
}

footer .container .row .contact .item {
  border-bottom: 1px solid white;
  padding: 10px 0;
}

footer .container .row .contact .item .icon {
  width: 30px;
  height: 30px;
  border-radius: 50%;
  line-height: 30px;
  background-color: rgba(0, 0, 0, 0.534);
  text-align: center;
  margin-right: 5px;
}

footer .container .row .contact .item .content {
  line-height: 16px;
}

footer .container .row .contact .item .content p {
  font-size: 16px;
  margin-bottom: 0;
}

footer .container .row .contact .item .content span {
  font-size: 14px;
}
</style>
