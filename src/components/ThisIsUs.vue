<template lang="">
  <section class="this-is-us py-3 bg-light">
    <div class="container">
      <div class="row title">
        <div class="col-md-8 mx-auto text">
          <div class="text-center">
            <h1 class="h3 mb-0">This is us</h1>
          </div>
          <hr class="mx-auto mt-1" />
          <p class="text-center text-muted">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Labore
            nihil et iste ea maxime cupiditate culpa architecto nemo, adipisci,
            at eligendi itaque est neque nam voluptates suscipit repudiandae
            officiis magnam?
          </p>
        </div>
      </div>

      <div class="row card-list my-3">
        <div class="col list">
          <div class="d-flex justify-content-center align-items-center group">
            <div class="box ">
              <span>
                <i class="fas fa-book-reader"></i>
              </span>
              <p>Study In Australia</p>
              <a href="#" class="btn-link">
                Dig In
                <i class="fas fa-long-arrow-alt-right"></i>
              </a>
            </div>
            <div class="box">
              <span>
                <i class="fas fa-book-reader"></i>
              </span>
              <p>Study In Japan</p>
              <a href="#" class="btn-link">
                Dig In
                <i class="fas fa-long-arrow-alt-right"></i>
              </a>
            </div>
            <div class="box">
              <span>
                <i class="fas fa-book-reader"></i>
              </span>
              <p>Study In UK</p>
              <a href="#" class="btn-link">
                Dig In
                <i class="fas fa-long-arrow-alt-right"></i>
              </a>
            </div>
            <div class="box">
              <span>
                <i class="fas fa-book-reader"></i>
              </span>
              <p>Study In USA</p>
              <a href="#" class="btn-link">
                Dig In
                <i class="fas fa-long-arrow-alt-right"></i>
              </a>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style scoped>
    .this-is-us .container .title .text hr {
  width: 80px;
  height: 2px;
  background-color: #140b0b;
}

.this-is-us .container .card-list .list .group {
  -ms-flex-wrap: wrap;
      flex-wrap: wrap;
}

.this-is-us .container .card-list .list .group .box {
  width: 200px;
  height: 130px;
  background-color: #EBEDEE;
  display: -webkit-box;
  display: -ms-flexbox;
  display: flex;
  -webkit-box-orient: vertical;
  -webkit-box-direction: normal;
      -ms-flex-direction: column;
          flex-direction: column;
  -webkit-box-pack: center;
      -ms-flex-pack: center;
          justify-content: center;
  border-radius: 5px;
  text-align: center;
  margin: 5px 10px;
  padding: 10px 3px;
}

.this-is-us .container .card-list .list .group .box:hover {
  -webkit-box-shadow: 1px 1px 15px lightgray;
          box-shadow: 1px 1px 15px lightgray;
  background-color: #ffffff;
}

.this-is-us .container .card-list .list .group .box span i {
  font-size: 2.5rem;
  margin-bottom: 10px;
  color: #45ACB0;
}

.this-is-us .container .card-list .list .group .box p {
  margin: 0;
  font-weight: 700;
}

.this-is-us .container .card-list .list .group .box a.btn-link {
  background-color: #1F2B33;
  text-decoration: none;
  color: white;
  width: -webkit-fit-content;
  width: -moz-fit-content;
  width: fit-content;
  padding: 1px 5px;
  border-radius: 5px;
  margin: auto;
}
</style>
