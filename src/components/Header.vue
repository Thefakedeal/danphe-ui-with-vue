<template lang="">
  <header>
    <div class="top">
      <div class="container py-1">
        <div class="row">
          <div class="col-md-6 icon-list">
            <ul
              class="list-unstyled d-flex justify-content-center justify-content-md-start m-0"
            >
              <li>
                <a href="#"><i class="fab fa-facebook-f"></i></a>
              </li>
              <li>
                <a href="#"><i class="fab fa-instagram"></i></a>
              </li>
              <li>
                <a href="#"><i class="fab fa-youtube"></i></a>
              </li>
              <li>
                <a href="#"><i class="fab fa-twitter"></i></a>
              </li>
            </ul>
          </div>
          <div class="col-md-6 text-md-end text-center text">
            <a href="#">Testimonial</a>
            <a href="#">Blog</a>
          </div>
        </div>
      </div>
    </div>
    <div class="info d-none d-md-block">
      <div class="container">
        <div class="row">
          <div class="col-md-4 logo">
            <a href="/" @click.prevent="$router.push({name:'Home'})">
              <img src="../assets/logo.png" alt="Danphe" />
            </a>
          </div>
          <div
            class="col-md-8 d-md-flex align-items-center justify-content-end detail"
          >
            <div class="d-flex align-items-center">
              <div class="icon">
                <i class="fas fa-phone-alt"></i>
              </div>
              <div class="call-us">
                <p class="mb-0">Call Us</p>
                <a href="#"><small>+977-9818691650</small></a>
              </div>
            </div>
            <div class="d-flex align-items-center">
              <div class="icon">
                <i class="fas fa-mail-bulk"></i>
              </div>
              <div class="email-us">
                <p class="mb-0">Email Us</p>
                <a href="#"><small>kfpanda009@gmail.com</small></a>
              </div>
            </div>
            <div class="d-flex align-items-center">
              <div class="icon">
                <i class="fas fa-book-open"></i>
              </div>
              <div class="visit-us">
                <p class="mb-0">Visit Us</p>
                <a href="#"><small>Dharan-8, Bargachi</small></a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <nav class="navbar navbar-expand-lg navbar-dark fixed-top w-100">
      <div class="container">
        <a class="navbar-brand d-block d-md-none" href="/" @click.prevent="$router.push({name:'Home'})">
          <img src="../assets/logo.png" alt="" />
        </a>
        <button
          class="navbar-toggler shadow-none border-0"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a
                class="nav-link side active"
                aria-current="page"
                href="/"
                @click.prevent="$router.push({name:'Home'})"
                >Home
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link side" href="/about" @click.prevent="$router.push({name:'About'})">About us </a>
            </li>
            <li class="nav-item">
              <a class="nav-link side" href="our-service.html">Our Service </a>
            </li>
            <li class="nav-item">
              <a class="nav-link side" href="partner_institue.html"
                >Partner Instiute
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link side" href="gallery.html">Gallery </a>
            </li>
            <li class="nav-item">
              <a class="nav-link side" href="test_preparation.html"
                >Test Preparation
              </a>
            </li>
            <li class="nav-item">
              <a class="nav-link side" href="blog.html">Blog </a>
            </li>
            <li class="nav-item">
              <a class="nav-link side" href="contact_us.html">Contact Us</a>
            </li>
            <li class="nav-item dropdown">
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Study Abroad
              </a>
              <ul
                class="dropdown-menu dropdown-menu-dark"
                aria-labelledby="navbarDropdown"
              >
                <li>
                  <a class="dropdown-item" href="#">Study In Australia</a>
                </li>
                <li><a class="dropdown-item" href="#">Study In Japan</a></li>
                <li><a class="dropdown-item" href="#">Study In UK</a></li>
              </ul>
            </li>
          </ul>
          <form class="d-flex">
            <div class="btn-group">
              <button
                type="button"
                class="btn dropdown-toggle shadow-none btn-sm search"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Search
              </button>
              <ul class="dropdown-menu dropdown-menu-md-end p-0">
                <li class="p-1">
                  <div class="input-group">
                    <input
                      type="text"
                      class="form-control shadow-none"
                      placeholder="Search"
                    />
                    <button
                      class="btn btn-outline-secondary shadow-none"
                      type="button"
                      id="button-addon2"
                    >
                      <i class="fas fa-search"></i>
                    </button>
                  </div>
                </li>
              </ul>
            </div>
          </form>
        </div>
      </div>
    </nav>
  </header>
</template>
<script>
export default {};
</script>
<style lang="scss" scoped>
.top {
  background-color: #1f2b33;
}

.top .container .row .icon-list ul li {
  margin-left: 8px;
}

.top .container .row .icon-list ul li a {
  text-decoration: none;
  color: #ebedee;
}

.top .container .row .icon-list ul li a:hover {
  color: #45acb0;
}

.top .container .row .text a {
  text-decoration: none;
  color: #ebedee;
  padding: 0 10px;
}

.top .container .row .text a:first-child {
  border-right: 1px solid #ffffff;
}

.info {
  background-color: #f1f1f1;
}

.info .container .row .logo img {
  width: 180px;
  height: 80px;
  -o-object-fit: cover;
  object-fit: cover;
}

.info .container .row .detail div {
  margin-right: 5px;
}

.info .container .row .detail div .icon {
  width: 35px;
  height: 35px;
  color: white;
  text-align: center;
  line-height: 35px;
  background-color: #45acb0;
  border-radius: 50%;
  margin-right: 5px;
}

.info .container .row .detail div .call-us,
.info .container .row .detail div .visit-us,
.info .container .row .detail div .email-us {
  line-height: 14px;
}

.info .container .row .detail div .call-us p,
.info .container .row .detail div .visit-us p,
.info .container .row .detail div .email-us p {
  font-weight: 700;
  line-height: 14px;
}

.info .container .row .detail div .call-us a,
.info .container .row .detail div .visit-us a,
.info .container .row .detail div .email-us a {
  text-decoration: none;
  color: #1f2b33;
}

.navbar {
  background-color: #1f2b33;
  border-top: 1px solid #ffffff;
  position: relative;
  z-index: 111111111;
}

.navbar .container .navbar-brand img {
  width: 120px;
  height: 50px;
  -o-object-fit: cover;
  object-fit: cover;
}

@media screen and (max-width: 768px) {
  .navbar .container .navbar-brand img {
    width: 150px;
  }
}

.navbar .container .navbar-toggler {
  color: #1f2b33;
}

.navbar .container .collapse .navbar-nav .nav-item .nav-link {
  color: #ebedee;
}

.navbar .container .collapse .navbar-nav .nav-item .side::after {
  content: "";
  padding: 0 5px;
}

.navbar .container .collapse .navbar-nav .nav-item .nav-link.active {
  color: #ffffff;
  font-weight: 600;
}

.navbar .container .collapse form div .search {
  background: #45acb0;
  color: #ebedee;
}

.navbar .container .collapse form div .dropdown-menu {
  width: 300px;
}

@media screen and (max-width: 992px) {
  .navbar .container .collapse .navbar-nav .nav-item .nav-link {
    color: #ebedee;
  }
  .navbar .container .collapse .navbar-nav .nav-item .side::after {
    content: "";
  }
}
</style>
