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
            <p>Проектная фабрика на базе мебельного производства</p>
          </div>
          <div class="anim-butt">
            <a href="https://api.whatsapp.com/send/?phone=77716419516&text&type=phone_number&app_absent=0" target="_blank"> 
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
            </a>
          </div>
          <div class="rassrotha">
            <a href="/rass">
            <button class="btn-rass">Рассрочка
            </button>
          </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>

@media (max-width: 1200px) {
  .rassrotha button{
  font-size: 18px;
 }
 /* .rassrotha{
  left: 840px;
 } */
 .animated-button{
  font-size: 18px;
 }
 .info h1{
  font-size: 38px;
 }
 .info p{
  line-height: 45px;
    font-size: 26px;
    max-width: 500px;
 }
}

@media (max-width: 760px) {
  .info h1 {
    font-size: 24px;
  }
  .info p{
    line-height: 1.2em;
    font-size: 16px;
    max-width: auto;
 }
 .animated-button .text {
  font-size: 14px;
 }
 .rassrotha{
  display: contents
 }
 .rassrotha button {
  font-size: 14px;
 }
}

@media (max-width: 480px) {
  .anim-butt {
    margin-bottom: 90px;
  }
}

.anim-butt a{
  text-decoration: none;
}

.anim-butt{
  margin-bottom: 50px;
}

.rassrotha button{
  cursor: pointer;
}

.rassrotha {
  right: 53px;
  bottom: 30px;
  position: absolute;
}

.btn-rass {
 position: relative;
 font-size: 17px;
 text-transform: uppercase;
 text-decoration: none;
 padding: 1em 2.5em;
 display: inline-block;
 border-radius: 6em;
 transition: all .2s;
 border: none;
 font-family: inherit;
 font-weight: 500;
 color: rgb(0, 0, 0);
 background-color: #fdc200;
}

.btn-rass:hover {
 transform: translateY(-3px);
 box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}

.btn-rass:active {
 transform: translateY(-1px);
 box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
}

.btn-rass::after {
 content: "";
 display: inline-block;
 height: 100%;
 width: 100%;
 border-radius: 100px;
 position: absolute;
 top: 0;
 left: 0;
 z-index: -1;
 transition: all .4s;
}

.btn-rass::after {
 background-color: #ffd857;
}

.btn-rass:hover::after {
 transform: scaleX(1.4) scaleY(1.6);
 opacity: 0;
}
</style>
