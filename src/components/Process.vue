<template>
  <div class="container-padding font-poppins">
    <div class="process-container margin-top">
      <h1 class="font-700 text-7xl mobile-4xl">
        Process<span class="font-orange">.</span>
      </h1>
    </div>
    <div class="row">
      <!-- START COL 1  -->
      <div class="col-xl-6 margin-top d-flex flex-column ">
        <div class="border-left ps-3">
          <h1 class="font-700 text-3xl mobile-3xl mt-3">
            Research<span class="font-orange">.</span>
          </h1>
          <p class="font-300 text-2xl mobile-2xl pt-2">
            Content & Visual Analysis, Market Research and Audience.
          </p>
        </div>
        <div class="border-left ps-3">
          <h1 class="font-700 text-3xl mobile-3xl mt-5">
            Prototype<span class="font-orange">.</span>
          </h1>
          <p class="font-300 text-2xl mobile-2xl pt-2">
            Low fidelity, Sitemaps, Structure and Element Preparation.
          </p>
        </div>
        <div class="border-left ps-3">
          <h1 class="font-700 text-3xl mobile-3xl mt-5">
            Design<span class="font-orange">.</span>
          </h1>
          <p class="font-300 text-2xl mobile-2xl pt-2">
            High fidelity & Development.
          </p>
        </div>
      </div>
      <!-- END COL 1  -->
      <!-- START COL 2  -->
      <div class="col-xl-6 text-center">
          <img :src="Peep" alt="" class="img1">
      </div>
      <!-- END COL 2  -->
    </div>
  </div>
</template>

<script>
import Peep from '../assets/peep1.svg';
export default {
    data: () => {
        return { 
            Peep,
        }
    }
};
</script>

<style>
@media(max-width:450px){
    .img1{
    padding-top: 20px;
    width: 100%;
}
}
</style>