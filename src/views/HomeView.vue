<script>
  import NavItem from '../components/NavItem.vue'

  export default {
    components: { NavItem }
  }
</script>

<template>
    <div class="intro">
      <div class="video">
        <video class="video_media" src="/video/video_2024-05-24_16-12-34.mp4" autoplay muted loop></video>
      </div>
    </div>
  <div class="main">
    <NavItem />
    <div class="iteminfo">
      <div class="wrapper">
      <div class="iteminfo__inner">
        <div class="info">
          <h1>
            <span> ПРЕМИАЛЬНАЯ МЕБЕЛЬ </span>
            <br>
             JMebel 
          </h1>
          <p>Проектная фабрика на базе мебельного и столярного производств</p>
        </div>
        <div class="anim-butt">
          <button class="animated-button">
            <svg viewBox="0 0 24 24" class="arr-2" xmlns="http://www.w3.org/2000/svg">
              <path
                d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z">
              </path>
            </svg>
            <span class="text">Оставить заявку</span>
            <span class="circle"></span>
            <svg viewBox="0 0 24 24" class="arr-1" xmlns="http://www.w3.org/2000/svg">
              <path
                d="M16.1716 10.9999L10.8076 5.63589L12.2218 4.22168L20 11.9999L12.2218 19.778L10.8076 18.3638L16.1716 12.9999H4V10.9999H16.1716Z">
              </path>
            </svg>
          </button>
        </div>
      </div>
    </div>
    </div>
  </div>
</template>

<style scoped>

</style>
