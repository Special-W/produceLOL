<template>
  <div class="swiper-container">
    <div class="swiper-wrapper">
      <router-link tag="div" class="swiper-slide" to="/DetailArticle1">
        <img src="../assets/img/slide1.jpg" alt="">
      </router-link>
      <router-link tag="div" class="swiper-slide" to="/DetailArticle2">
        <img src="../assets/img/slide2.jpg" alt="">
      </router-link>
      <div class="swiper-slide">
        <img src="../assets/img/slide3.jpg" alt="">
      </div>
      <div class="swiper-slide">
        <img src="../assets/img/slide4.jpg" alt="">
      </div>
    </div>
    <div class="swiper-pagination"></div>
  </div>
</template>

<script>
  import Swiper from 'swiper'
    export default {
      name: "slider",
      mounted(){
        var mySwiper = new Swiper('.swiper-container', {
          autoplay:true,
          loop:true,
          pagination: {
            el: '.swiper-pagination',
          },
        })
      }
    }
</script>

<style scoped>
  .swiper-slide img{
    width: 100%;
    height: 200px;
  }
</style>
