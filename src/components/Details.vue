<script setup>
const details = "Voluptatem dignissimos provident quasi corporis voluptates sit assumenda.";
const slogan = "Lorem ipsum dolor sit amet, consectetur adipiscing elit incididunt ut labore et dolore";
const option = "Ullamco laboris nisi ut aliquip ex ea commodo consequat.";
const optiontwo = " Duis aute irure dolor in reprehenderit in voluptate velit."; 
const optionthree = "Iure at voluptas aspernatur dignissimos doloribus repudiandae.";  
const optionfour = "Est ipsa assumenda id facilis nesciunt placeat sed doloribus praesentium."; 
const des = "Voluptas nisi in quia excepturi nihil voluptas nam et ut. Expedita omnis eum consequatur non. Sed in asperiores aut repellendus. Error quisquam ab maiores. Quibusdam sit in officia";
       
</script>

<template>
  <section id="details" class="details">
      <div class="container">

        <div class="row content">
          <div class="col-md-4" data-aos="fade-right">
            <img src="/src/assets/img/details-1.png" class="img-fluid" alt="">
          </div>
          <div class="col-md-8 pt-4" data-aos="fade-up">
            <h3>{{ details }}</h3>
            <p class="fst-italic">
             {{ slogan }}
            </p>
            <ul>
              <li><i class="bi bi-check"></i> {{ option }}</li>
              <li><i class="bi bi-check"></i>{{ optiontwo }}</li>
              <li><i class="bi bi-check"></i> {{ optionthree }}</li>
              <li><i class="bi bi-check"></i> {{ optionfour }}</li>
            </ul>
            <p>
              {{ des }}
            </p>
          </div>
        </div>

        <div class="row content">
          <div class="col-md-4 order-1 order-md-2" data-aos="fade-left">
            <img src="/src/assets/img/details-2.png" class="img-fluid" alt="">
          </div>
          <div class="col-md-8 pt-5 order-2 order-md-1" data-aos="fade-up">
            <h3>Corporis temporibus maiores provident</h3>
            <p class="fst-italic">
             {{ details }}
            </p>
            <p>
              Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
              velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
              culpa qui officia deserunt mollit anim id est laborum
            </p>
            <p>
              {{ des }}
            </p>
          </div>
        </div>

        <div class="row content">
          <div class="col-md-4" data-aos="fade-right">
            <img src="/src/assets/img/details-3.png" class="img-fluid" alt="">
          </div>
          <div class="col-md-8 pt-5" data-aos="fade-up">
            <h3>{{ title }}</h3>
            <p>{{ slogan }}</p>
            <ul>
              <li><i class="bi bi-check"></i> {{ option }}</li>
              <li><i class="bi bi-check"></i> {{ optiontwo }}</li>
              <li><i class="bi bi-check"></i> {{ optionthree }}</li>
            </ul>
            <p>
              {{ des }}
            </p>
            <p>
              Suscipit enim et. Ut optio esse quidem quam reiciendis esse odit excepturi. Vel dolores rerum soluta explicabo vel fugiat eum non.
            </p>
          </div>
        </div>

        <div class="row content">
          <div class="col-md-4 order-1 order-md-2" data-aos="fade-left">
            <img src="/src/assets/img/details-4.png" class="img-fluid" alt="">
          </div>
          <div class="col-md-8 pt-5 order-2 order-md-1" data-aos="fade-up">
            <h3>Quas et necessitatibus eaque impedit ipsum animi consequatur incidunt in</h3>
            <p class="fst-italic">
           {{ details }}
            </p>
            <p>
              Ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate
              velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in
              culpa qui officia deserunt mollit anim id est laborum
            </p>
            <ul>
              <li><i class="bi bi-check"></i> {{option}}</li>
              <li><i class="bi bi-check"></i> {{optionfour}}</li>
              <li><i class="bi bi-check"></i> {{optionthree}}</li>
            </ul>
          </div>
        </div>

      </div>
    </section>
</template>



<style scoped>

</style>
