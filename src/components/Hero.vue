<script setup>
const title = "App landing page template";
const slogan = "Lorem ipsum dolor sit amet, tota senserit percipitur ius ut, usu et fastidii forensibus voluptatibus. His ei nihil feugait";
</script>
<template>
<section id="hero" class="d-flex align-items-center">
<div class="container">
  <div class="row">
    <div class="col-lg-6 d-lg-flex flex-lg-column justify-content-center align-items-stretch pt-5 pt-lg-0 order-2 order-lg-1" data-aos="fade-up">
      <div>
        <h1>{{ title }}</h1>
        <h2>{{ slogan }}</h2>
        <a href="#" class="download-btn"><i class="bx bxl-play-store"></i> Google Play</a>
        <a href="#" class="download-btn"><i class="bx bxl-apple"></i> App Store</a>
      </div>
    </div>
    <div class="col-lg-6 d-lg-flex flex-lg-column align-items-stretch order-1 order-lg-2 hero-img" data-aos="fade-up">
      <img src="/src/assets/img/hero-img.png" class="img-fluid" alt="">
    </div>
  </div>
</div>
</section>
</template>

<style  scoped>

</style>