<template lang="">
  <section class="about-us py-5">
    <div class="container">
      <div class="row title">
        <div class="col-md-8 mx-auto text">
          <div class="text-center">
            <h1 class="h3 mb-0">About us</h1>
          </div>
          <hr class="mx-auto mt-1" />
        </div>
      </div>
      <div class="row feature my-3">
        <div class="col-md-6 my-3 option">
          <div class="card p-2">
            <h1 class="h5 mb-0 fw-bold text-muted mx-1">
              Wellcome To Danphe Consultancy
            </h1>
            <div class="accordion my-3" id="danpheAccordian">
              <div class="accordion-item border-0">
                <h2 class="accordion-header" id="headingOne">
                  <button
                    class="accordion-button shadow-none border-0"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#ourMission"
                    aria-expanded="true"
                    aria-controls="ourMission"
                  >
                    Our Mission
                  </button>
                </h2>
                <div
                  id="ourMission"
                  class="accordion-collapse collapse show"
                  aria-labelledby="headingOne"
                  data-bs-parent="#danpheAccordian"
                >
                  <div class="accordion-body">
                    <p>
                      Lorem ipsum dolor sit amet consectetur adipisicing elit.
                      Molestiae dicta adipisci deserunt inventore.
                      Exercitationem sapiente, facilis officiis repellat ipsum
                      eos consequatur doloribus nesciunt libero velit, aperiam
                      laboriosam ducimus aliquam. Amet?
                    </p>
                  </div>
                </div>
              </div>
              <div class="accordion-item border-0">
                <h2 class="accordion-header" id="headingTwo">
                  <button
                    class="accordion-button collapsed shadow-none"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#ourVision"
                    aria-expanded="false"
                    aria-controls="ourVision"
                  >
                    Our Vision
                  </button>
                </h2>
                <div
                  id="ourVision"
                  class="accordion-collapse collapse"
                  aria-labelledby="headingTwo"
                  data-bs-parent="#danpheAccordian"
                >
                  <div class="accordion-body">
                    <p>
                      Lorem ipsum dolor sit amet consectetur adipisicing elit.
                      Molestiae dicta adipisci deserunt inventore.
                      Exercitationem sapiente, facilis officiis repellat ipsum
                      eos consequatur doloribus nesciunt libero velit, aperiam
                      laboriosam ducimus aliquam. Amet?
                    </p>
                  </div>
                </div>
              </div>
              <div class="accordion-item border-0">
                <h2 class="accordion-header" id="headingThree">
                  <button
                    class="accordion-button collapsed shadow-none"
                    type="button"
                    data-bs-toggle="collapse"
                    data-bs-target="#collapseThree"
                    aria-expanded="false"
                    aria-controls="collapseThree"
                  >
                    Our Achievement
                  </button>
                </h2>
                <div
                  id="collapseThree"
                  class="accordion-collapse collapse"
                  aria-labelledby="headingThree"
                  data-bs-parent="#danpheAccordian"
                >
                  <div class="accordion-body">
                    <p>
                      Lorem ipsum dolor sit amet consectetur adipisicing elit.
                      Molestiae dicta adipisci deserunt inventore.
                      Exercitationem sapiente, facilis officiis repellat ipsum
                      eos consequatur doloribus nesciunt libero velit, aperiam
                      laboriosam ducimus aliquam. Amet?
                    </p>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-md-6 my-3 order-md-first video">
          <iframe
            width="100%"
            height="300"
            src="https://www.youtube.com/embed/xVN73mUSzKw"
            title="YouTube video player"
            frameborder="0"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen
          ></iframe>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
export default {};
</script>
<style scoped>
.about-us .container .title .text hr {
  width: 80px;
  height: 2px;
  background-color: #140b0b;
}

.about-us .container .feature .video iframe {
  border-radius: 5px;
}

.about-us .container .feature .option .accordion .accordion-item h2 {
  margin: 0;
}

.about-us .container .feature .option .accordion .accordion-item h2 button {
  padding: 15px 8px;
  font-weight: 700;
}

.about-us
  .container
  .feature
  .option
  .accordion
  .accordion-item
  h2
  button:focus {
  background-color: whitesmoke;
  color: #1f2b33;
}

.about-us
  .container
  .feature
  .option
  .accordion
  .accordion-item
  .accordion-collapse
  .accordion-body {
  padding: 10px;
}
</style>
