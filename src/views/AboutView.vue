<script>
  import NavItem from '../components/NavItem.vue'
  
  export default {
    components: { NavItem },
  }
</script>

<template>
  <NavItem color="light" />
  <div class="nav_about">
    <a href="/">Главная</a> 
    <p>/ О нас</p>
  </div>
  <div class="about">
    <h2>О нас</h2>
  </div>
  <div class="conteiner_about">
    <div class="baner_about">
      <div class="front_content">
        <h3>
          JMebel
        </h3>
        <p>Кухня — это особое пространство в квартире. Здесь создаются кулинарные шедевры и воплощаются в жизнь самые смелые эксперименты. Кроме того, здесь часто проводятся тихие семейные вечера и встречи с близкими друзьями. Поэтому очень важно создать не только функциональное, но и стильное пространство. Кухни от производителя Orange Park Joinery готовы наполнить ваш дом уютом, гармонией и теплом.</p>
      </div>
      <img src="/img-logo/Front_content1.jpg" alt="">
    </div>
  </div>
  <div class="conteiner_about">
    <div class="baner_about">
      <img src="/img-logo/Front_content2.jpg" alt="">
      <div class="front_content">
        <h3>
          ПРЕИМУЩЕСТВА
        </h3>
        <p>Наша мебельная фабрика работает в России с 1998 года. За это время мы реализовали много авторских проектов премиум-класса, радующих первоклассной эргономикой и эксклюзивным дизайном. Мы готовы предложить:
        • коллектив профессионалов. В нашем штате есть первоклассные специалисты, хорошо знающие свое дело;
        • собственный проектный отдел. Мы возьмем за основу ваш дизайн-проект и поможем воплотить в жизнь любые ваши идеи и разработать мебель по индивидуальным размерам даже в нестандартных помещениях;
        • разработку проекта под ключ. Вам не придется искать разных подрядчиков, чтобы грамотно укомплектовать пространство. Мы можем создать для вас любую корпусную мебель в единой стилистике.
        Наша проектная фабрика получает фурнитуру и сырье напрямую от европейских поставщиков.</p>
      </div>
    </div>
  </div>
  <div class="conteiner_about">
    <div class="baner_about">
      <div class="front_content">
        <h3>
          СТОЛЯРНОЕ
          И МЕБЕЛЬНОЕ
          ПРОИЗВОДСТВО
        </h3>
        <p>Собственное производство премиум-уровня. Чтобы мы рассчитали стоимость проекта, вы можете оставить заявку с указанием телефона и вашего города. Специалист проектного отдела оперативно выполнит расчёт и свяжется с вами.</p>
        <a href="tel:+77716419516">
        <button>Связатся с нами</button></a>
      </div>
      <img src="/img-logo/Front_content3.jpg" alt="">
    </div>
  </div>
  <div class="conteiner_about">
    <div class="baner_about">
      <img src="/img-logo/Front_content4.jpg" alt="">
      <div class="front_content">
        <h3>
          СТИЛИ КУХОНЬ
        </h3>
        <p>Мы не работаем по шаблону. Как будет выглядеть ваша будущая кухня, решаете только вы. Мы учитываем все пожелания и можем воплотить в жизнь любые варианты. Классические кухни. Это грамотный тандем простоты, строгости и изящества. Здесь нет лишних деталей, а каждый элемент находится на своем месте. Натуральные материалы благородных тонов и качественная фурнитура направлены на создание уюта и гармонии. Современные кухни. Это неординарный подход к оформлению интерьера. В стилистике гармонично сочетаются простые формы, современные материалы и высокотехнологичное оборудование. Они наполняют помещение комфортом, функциональностью и неповторимостью. Вы можете познакомиться с фото наших работ в каталоге на сайте, Телеграм-канале, YouTube, группе «Вконтакте», либо посетив один из наших шоу-румов. Заказать разработку индивидуального дизайнерского проекта можно на официальном сайте мебельной фабрики Orange Park Joinery. Заполните форму обратной связи, и наши специалисты свяжутся с вами для обсуждения условий заказа.</p>
      </div>
    </div>
  </div>
</template>

<style>
@media (min-width: 1024px) {
  .about {
    justify-content: center;
    align-items: center;
  }
}

body {
  background-color: black;
  /* display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100hp; */
}

.conteiner_about{
  margin: 152px auto;
  width: 70%;

}

.about h2{
  color: #fdc200;
  font-size: 43px;
    line-height: 43px;
    text-transform: uppercase;
    letter-spacing: 0.6px;
    text-align: center;
    /* margin: 0 0 50% 45%; */
}

.front_content {
  /* margin: 0 592px 0 0; */
    padding: 35px 0 0 0;
    line-height: 23px;
    text-align: right;
}

.front_content h3 {
  color: #fdc200;
  font-size: 42px;
    line-height: 41px;
    margin: 0 0 39px 0;
    padding: 0;
    /* text-transform: uppercase; */
    letter-spacing: 0.5px;
}

.front_content p {
  color: #fff;
  font-size: 16px;
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

.baner_about img {
  max-width:490px ;
  float: right;
  border: 3px solid #fdc200;
  border-radius: 30px;
  margin-left: 30px;
}

.baner_about {
display: flex;
  gap: 50px;
  align-items: center;
}
</style>
