<template>
  <section id="about" class="container-padding">
      <div class="font-poppins margin-top">
          <div class="row">
              <!-- START COL 1  -->
              <div class="col-xl-6 text-center">
                  <img :src="PeepSit" alt="" class="img2">
              </div>
              <!-- END COL 1  -->
              <!-- START COL 2  -->
              <div class="col-xl-6">
                  <h1 class="font-700 text-7xl mobile-4xl">About<span class="font-orange">.</span></h1>
                  <p class="font-300 text-2xl mobile-2xl pt-5">Born in Manila, 1998. Ever since I was young, I was hooked and fascinated about the internet and how websites work. I am determined to continue to seek knowledge and improvements to fully grasp and hone my skills.</p>
                  <h1 class="font-700 text-7xl mobile-4xl pt-5">Technologies<span class="font-orange">.</span></h1>
                  <img :src="Tech" alt="" class="img3 pt-5">
              </div>
              <!-- END COL 2  -->
          </div>
      </div>
  </section>
</template>

<script>
import PeepSit from '../assets/peep2.svg';
import Tech from '../assets/tech1.svg';
export default {
    data: () => {
        return { 
            PeepSit,
            Tech,
        }
    }
}
</script>

<style>
@media(max-width:1080px){
    .img2{
        display: none;
    }
    .img3{
        width:95%;
    }
}
@media (max-width:450px){
    .img2{
        display: none;
    }
    .img3{
        width: 95%;
    }
}
</style>