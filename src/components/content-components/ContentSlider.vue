<!--
<template>
  <div class="slider">
    <div class="container">
      <div class="row">
        <swiper :options="swiperOption" class="sliderCont">
          <swiper-slide class="swiper-slide ss1">
            <h2>캡틴 마블<em>Captain Marvel</em></h2>
            <p>새로운 히어로, 어벤져스의 희망</p>
          </swiper-slide>
          <swiper-slide class="swiper-slide ss2">
            <h2>Avengers<em>End Game</em></h2>
            <p>역대 최단 기간 1000만 관객 돌파 기록</p>
          </swiper-slide>
          <swiper-slide class="swiper-slide ss3">
            <h2>Game Of Thrones <em>Season 3</em></h2>
            <p>The Complete Third Season</p>
          </swiper-slide>
          <swiper-slide class="swiper-slide ss4">
            <h2>Game Of Thrones <em>Season 3</em></h2>
            <p>The Complete Third Season</p>
          </swiper-slide>
          <div class="swiper-pagination" slot="pagination"></div>
          <div class="swiper-button-prev" slot="button-prev"></div>
          <div class="swiper-button-next" slot="button-next"></div>
        </swiper>
      </div>
    </div>
  </div>
</template>
-->
<template>
  <div class="slider">
    <div class="container">
      <div class="row">
        <swiper :options="swiperOption" class="sliderCont">
          <swiper-slide class="swiper-slide ss1">
            <h2>캡틴 마블<em>Captain Marvel</em></h2>
            <p>새로운 히어로, 어벤져스의 희망</p>
          </swiper-slide>
          <swiper-slide class="swiper-slide ss2">
            <h2>Avengers<em>End Game</em></h2>
            <p>역대 최단 기간 1000만 관객 돌파 기록</p>
          </swiper-slide>
          <swiper-slide class="swiper-slide ss3">
            <h2>Game Of Thrones <em>Season 3</em></h2>
            <p>The Complete Third Season</p>
          </swiper-slide>
          <swiper-slide class="swiper-slide ss4">
            <h2>Game Of Thrones <em>Season 3</em></h2>
            <p>The Complete Third Season</p>
          </swiper-slide>
          <div class="swiper-pagination" slot="pagination"></div>
          <div class="swiper-button-prev" slot="button-prev"></div>
          <div class="swiper-button-next" slot="button-next"></div>
        </swiper>
      </div>
    </div>
  </div>
</template>

<script>
import "swiper/dist/css/swiper.css";
import { swiper, swiperSlide } from "vue-awesome-swiper";

export default {
  data() {
    return {
      swiperOption: {
        slidesPerView: 1,
        spaceBetween: 30,
        loop: true,
        pagination: {
          el: ".swiper-pagination",
          clickable: true
        },
        navigation: {
          nextEl: ".swiper-button-next",
          prevEl: ".swiper-button-prev"
        }
      }
    };
  },
  components: {
    swiper,
    swiperSlide
  }
};
</script>

<style scoped>
</style>