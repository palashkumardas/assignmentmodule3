<script setup>
const title = "Pricing";
const slogan = "Quia fugiat sit in iste officiis commodi quidem hic quas.";
const price = "Quam adipiscing vitae proin";
const pricetwo = "Nec feugiat nisl pretium";
const pricethree = "Nulla at volutpat diam uteera";
const pricefour = "Pharetra massa massa ultricies";
</script>

<template>
   <section id="pricing" class="pricing">
      <div class="container">

        <div class="section-title">
          <h2>{{ title }}</h2>
          <p>{{ slogan }} </p>
        </div>

        <div class="row no-gutters">

          <div class="col-lg-4 box" data-aos="fade-right">
            <h3>Free</h3>
            <h4>$0<span>per month</span></h4>
            <ul>
              <li><i class="bx bx-check"></i> {{ price }}</li>
              <li><i class="bx bx-check"></i> {{ pricetwo }}</li>
              <li><i class="bx bx-check"></i> {{ pricethree }}</li>
              <li><i class="bx bx-x"></i> <span>{{ pricefour }}</span></li>
            </ul>
            <a href="#" class="get-started-btn">Get Started</a>
          </div>

          <div class="col-lg-4 box featured" data-aos="fade-up">
            <h3>Business</h3>
            <h4>$29<span>per month</span></h4>
            <ul>
              <li><i class="bx bx-check"></i> {{ price }}</li>
              <li><i class="bx bx-check"></i> {{ pricetwo }}</li>
              <li><i class="bx bx-check"></i> {{ pricethree }}</li>
              <li><i class="bx bx-x"></i> <span>{{ pricefour }}</span></li>
            </ul>
            <a href="#" class="get-started-btn">Get Started</a>
          </div>

          <div class="col-lg-4 box" data-aos="fade-left">
            <h3>Developer</h3>
            <h4>$49<span>per month</span></h4>
            <ul>
              <li><i class="bx bx-check"></i> {{ price }}</li>
              <li><i class="bx bx-check"></i> {{ pricetwo }}</li>
              <li><i class="bx bx-check"></i> {{ pricethree }}</li>
              <li><i class="bx bx-x"></i> <span>{{ pricefour }}</span></li>
            </ul>
            <a href="#" class="get-started-btn">Get Started</a>
          </div>

        </div>

      </div>
    </section>
</template>



<style scoped>

</style>
