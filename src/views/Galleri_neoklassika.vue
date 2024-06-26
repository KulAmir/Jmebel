<script>
import NavItem from '../components/NavItem.vue'
import GalleryItem from '../components/GalleryItem.vue'

export default {
  components: { NavItem, GalleryItem },

}
</script>


<template>
  <NavItem color="light" />
  <div class="nav_about">
    <a href="/">Главная</a>
    <a href="/galeri">
      <p>/ Галерея</p>
    </a>
    <p>/ Неоклассика</p>
  </div>
  <div class="about">
    <h2>Неоклассика</h2>
    <p>Неоклассический: современная адаптация классического стиля. Классические рамочные фасады с облегченным рисунком
      рамки и фурнитурой в современном стиле. Неоклассике присущи простые и четкие линии. Сложный декор и замысловатая
      фурнитура классики заменяются строгой функциональностью форм и деталей.
      Для неоклассической кухни не обязательно симметричное построение, считающееся основой классического стиля, что
      позволяет применять этот стиль практически в любых помещениях, независимо от планировки.
      Кухни в стиле неоклассика реже, чем классические, используют древесные текстуры
      , отдавая предпочтения монохромным оттенкам современной цветовой гаммы. Вместо патины
      и позолоты применяются хром и чернение.</p>
  </div>
  <div class="galleri_button">
    <a href="/galeri"> <button class="g_button1">Все проекты</button></a>
    <a href="/mod"><button class="g_button2">Модерн</button></a>
    <a href="/neo"><button class="g_button3">Неоклассика</button></a>
  </div>
  
  <GalleryItem :imgSources="[
    '/img-logo/Gallere_neo/n1.jpg',
    '/img-logo/Gallere_neo/n2.jpg',
    '/img-logo/Gallere_neo/n3.jpg',
    '/img-logo/Gallere_neo/n4.jpg',
    '/img-logo/Gallere_neo/n5.jpg',
    '/img-logo/Gallere_neo/n6.jpg',
    '/img-logo/Gallere_neo/n7.jpg',
    '/img-logo/Gallere_neo/n8.jpg',
    '/img-logo/Gallere_neo/n9.jpg',
    '/img-logo/Gallere_neo/n10.jpg',
    '/img-logo/Gallere_neo/n11.jpg',
    '/img-logo/Gallere_neo/n12.jpg',
    '/img-logo/Gallere_neo/n13.jpg',
    '/img-logo/Gallere_neo/n14.jpg',
    '/img-logo/Gallere_neo/n15.jpg',
    '/img-logo/Gallere_neo/n16.jpg',
  ]" />


</template>

<style>


body {
  background-color: black;
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

.about p {
  color: #fff;
  max-width: 1085px;
  margin-left: 213px;
  text-align: center;
  margin-bottom: 50px;
  font-size: 17px;
  line-height: 27px;
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

@media (max-width: 1100px){
  .about p {
    margin: 0 20px 20px;
    font-size: 14px;
    line-height: 20px;
  }
}
</style>