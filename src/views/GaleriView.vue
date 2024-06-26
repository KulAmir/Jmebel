<script>
import NavItem from '../components/NavItem.vue'
import { Swiper, SwiperSlide } from 'swiper/vue';
import { Navigation } from 'swiper/modules';

import 'swiper/css/bundle';
import 'swiper/css/navigation';

export default {
  components: {
    NavItem,
    Swiper,
    SwiperSlide
  },
  setup() {
    const onSwiper = (swiper) => {
      console.log(swiper);
    };
    const onSlideChange = () => {
      console.log('slide change');
    };
    return {
      onSwiper,
      onSlideChange,
      modules: [Navigation],
    };
  },
}
</script>

<template>
  <NavItem color="light" />
  <div class="nav_about">
    <a href="/">Главная</a>
    <p>/ Галерея</p>
  </div>
  <div class="about">
    <h2>Галерея</h2>
  </div>
  <div class="galleri_button">
    <a href="/galeri"> <button class="g_button1">Все проекты</button></a>
    <a href="/mod"><button class="g_button2">Модерн</button></a>
    <a href="/neo"><button class="g_button3">Неоклассика</button></a>
  </div>

  <div class="about">
    <h2>Кухня</h2>
  </div>

  <swiper :modules="modules" :slides-per-view="3" :space-between="50" navigation :pagination="{ clickable: true }"
    :scrollbar="{ draggable: true }" @swiper="onSwiper" @slideChange="onSlideChange">
    <swiper-slide><img src="/img-logo/Gallere_neo/n1.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n2.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n3.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n4.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n5.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n6.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m1.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m2.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m3.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m4.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m5.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m6.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m7.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m8.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m9.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m10.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m11.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m12.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m13.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m14.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m15.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m16.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/m17.jpg" width="500"></swiper-slide>
  </swiper>

  <div class="about">
    <h2>Шкафы</h2>
  </div>

  <swiper :modules="modules" :slides-per-view="3" :space-between="50" navigation :pagination="{ clickable: true }"
    :scrollbar="{ draggable: true }" @swiper="onSwiper" @slideChange="onSlideChange">
    <swiper-slide><img src="/img-logo/Gallere_mod/s1.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/s2.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/s3.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/s4.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n8.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n9.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n10.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n11.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n12.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/s10.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n12.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/s12.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/s13.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n13.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/s15.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/s16.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n14.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_mod/s18.jpg" width="500"></swiper-slide>
    <swiper-slide><img src="/img-logo/Gallere_neo/n16.jpg" width="500"></swiper-slide>
  
  </swiper>

</template>

<style>

@media (max-width: 1100px){
  .swiper-slide{
    display:contents;
  }
  .swiper-wrapper{
    font-size: 50px;
  }
}

:root {
  --swiper-navigation-size: 73px;
}

.swiper-wrapper img {
  border-radius: 85px;
  height: 610px;
  border: 5px solid #fdc200;
}

.swiper-button-next:after,
.swiper-rtl .swiper-button-prev:after {
  color: rgb(255, 173, 22);
}

.swiper-button-prev:after,
.swiper-rtl .swiper-button-next:after {
  content: 'prev';
  color: rgb(255, 173, 22);
}

.swiper-horizontal {
    margin-bottom: 75px;
  }

body {
  background-color: black;
}

.about h3{
  color: #fdc200;
  font-size: 43px;
  line-height: 43px;
  text-transform: uppercase;
  letter-spacing: 0.6px;
  text-align: center;
  margin-bottom: 50px;
}

.about h2 {
  color: #fdc200;
  font-size: 43px;
  line-height: 43px;
  text-transform: uppercase;
  letter-spacing: 0.6px;
  text-align: center;
  margin-bottom: 50px;
}

.nav_about {
  color: #C3C3C3;
  text-align: center;
  margin-bottom: 15px;
  font-size: 13px;
}

.nav_about p {
  margin-left: 10px;
  display: inline-block;
}

.nav_about a {
  text-decoration: none;
  color: #C3C3C3;
}

.galleri_button {
  text-align: center;
  margin-bottom: 50px;
}

.galleri_button button {
  appearance: none;
  background-color: #a78600;
  ;
  border: 0.125em solid #fdc200;
  border-radius: 0.9375em;
  box-sizing: border-box;
  color: #3B3B3B;
  cursor: pointer;
  display: inline-block;
  font-family: Roobert, -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
  font-size: 16px;
  font-weight: 600;
  line-height: normal;
  margin: 15px;
  min-height: 3.75em;
  min-width: 0;
  outline: none;
  padding: 1em 5.0em;
  text-align: center;
  text-decoration: none;
  transition: all 300ms cubic-bezier(.23, 1, 0.32, 1);
  user-select: none;
  -webkit-user-select: none;
  touch-action: manipulation;
  will-change: transform;
}

.galleri_button button:disabled {
  pointer-events: none;
}

.galleri_button button:hover {
  color: #fff;
  background-color: #fdc200;
  box-shadow: rgba(0, 0, 0, 0.25) 0 8px 15px;
  transform: translateY(-2px);
}

.galleri_button button:active {
  box-shadow: none;
  transform: translateY(0);
}
</style>