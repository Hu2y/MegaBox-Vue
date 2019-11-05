<template>
  <section id="banner">
    <h2 class="ir_so">최신 영화 소식</h2>
    <banner-menu></banner-menu>
    <content-slider></content-slider>
    <content-movie></content-movie>
    <content-event></content-event>
  </section>
</template>

<script>
import BannerMenu from './content-components/BannerMenu'
import ContentSlider from './content-components/ContentSlider'
import ContentMovie from './content-components/ContentMovie'
import ContentEvent from './content-components/ContentEvent'

export default {
  components: {
    BannerMenu,
    ContentSlider,
    ContentMovie,
    ContentEvent
  }
}
</script>

<style>

</style>