<script setup>
const subtitle = "App Features";
const titleone = "Corporis voluptates sit";
const titletwo = "Ullamco laboris nisi";
const titlethree = "Labore consequatur";
const titlefour = "Beatae veritatis";
const titlefive = "Molestiae dolor";
const titlesix = "Explicabo consectetur";

const detailsone = "Consequuntur sunt aut quasi enim aliquam quae harum pariatur laboris nisi ut aliquip";
const detailstwo = "Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt";
const detailsthree = "Aut suscipit aut cum nemo deleniti aut omnis. Doloribus ut maiores omnis facere";
const detailsfour = "Expedita veritatis consequuntur nihil tempore laudantium vitae denat pacta";
const detailsfive = "Et fuga et deserunt et enim. Dolorem architecto ratione tensa raptor marte";
const detailssix = "Est autem dicta beatae suscipit. Sint veritatis et sit quasi ab aut inventore";

const features = "Magnam dolores commodi suscipit. Necessitatibus eius consequatur ex aliquid fuga eum quidem. Sit sint consectetur velit. Quisquam quos quisquam cupiditate. Et nemo qui impedit suscipit alias ea. Quia fugiat sit in iste officiis commodi quidem hic quas.";
</script>

<template>
  <section id="features" class="features">
      <div class="container">

        <div class="section-title">
          <h2>{{ subtitle }}</h2>
          <p>{{ features }}</p>
        </div>

        <div class="row no-gutters">
          <div class="col-xl-7 d-flex align-items-stretch order-2 order-lg-1">
            <div class="content d-flex flex-column justify-content-center">
              <div class="row">
                <div class="col-md-6 icon-box" data-aos="fade-up">
                  <i class="bx bx-receipt"></i>
                  <h4>{{ titleone }}</h4>
                  <p>{{ detailsone }}</p>
                </div>
                <div class="col-md-6 icon-box" data-aos="fade-up" data-aos-delay="100">
                  <i class="bx bx-cube-alt"></i>
                  <h4>{{ titletwo }}</h4>
                  <p>{{ detailstwo }}</p>
                </div>
                <div class="col-md-6 icon-box" data-aos="fade-up" data-aos-delay="200">
                  <i class="bx bx-images"></i>
                  <h4>{{ titlethree }}</h4>
                  <p>{{ detailsthree }}</p>
                </div>
                <div class="col-md-6 icon-box" data-aos="fade-up" data-aos-delay="300">
                  <i class="bx bx-shield"></i>
                  <h4>{{ titlefour }}</h4>
                  <p>{{ detailsfour }}</p>
                </div>
                <div class="col-md-6 icon-box" data-aos="fade-up" data-aos-delay="400">
                  <i class="bx bx-atom"></i>
                  <h4>{{ titlefive }}</h4>
                  <p>{{ detailsfive }}</p>
                </div>
                <div class="col-md-6 icon-box" data-aos="fade-up" data-aos-delay="500">
                  <i class="bx bx-id-card"></i>
                  <h4>{{ titlesix }}</h4>
                  <p>{{ detailssix }}</p>
                </div>
              </div>
            </div>
          </div>
          <div class="image col-xl-5 d-flex align-items-stretch justify-content-center order-1 order-lg-2" data-aos="fade-left" data-aos-delay="100">
            <img src="/src/assets/img/features.svg" class="img-fluid" alt="">
          </div>
        </div>

      </div>
    </section>
</template>

<style scoped>

</style>