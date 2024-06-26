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
    <h3>Добро пожаловать в мир удобства и стиля с Jmebel!</h3>
  </div>
  <div class="conteiner_about">
    <div class="baner_about">
      <div class="front_content">
        <h3>
          Мы
        </h3>
        <p>Компания, вдохновленная вашими потребностями в комфортной и функциональной мебели для вашего дома. В Jmebel
          мы стремимся создавать качественную корпусную мебель, которая не только сочетает в себе функциональность и
          эстетику, но и отражает ваш уникальный стиль жизни.</p>
      </div>
      <img src="/img-logo/Front_content1.jpg" alt="">
    </div>
  </div>
  <div class="conteiner_about">
    <div class="baner_about">
      <img src="/img-logo/Gallere_neo/n5.jpg" alt="">
      <div class="front_content">
        <h3>
          Наша миссия
        </h3>
        <p>Предоставить вам широкий выбор мебельных решений, от классических до современных дизайнов, чтобы ваш дом стал
          идеальным отражением вашей индивидуальности. Мы заботимся о каждой детали - от выбора высококачественных
          материалов до инновационных решений в дизайне, чтобы обеспечить вам продукцию, которая будет радовать вас
          многие годы.</p>
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
        <p>Собственное производство премиум-уровня. Чтобы мы рассчитали стоимость проекта, вы можете оставить заявку с
          указанием телефона. Специалист проектного отдела оперативно выполнит расчёт и свяжется с вами.</p>
        <a href="https://api.whatsapp.com/send/?phone=77716419516&text&type=phone_number&app_absent=0" target="_blank">
          <button>Связатся с нами</button></a>
      </div>
      <img src="/img-logo/Front_content3.jpg" alt="">
    </div>
  </div>
  <div class="conteiner_about">
    <div class="baner_about">
      <img src="/img-logo/Gallere_neo/n4.jpg" alt="">
      <div class="front_content">
        <h3>
          СТИЛИ КУХОНЬ
        </h3>
        <p>Мы не работаем по шаблону. Как будет выглядеть ваша будущая кухня, решаете только вы. Мы учитываем все
          пожелания и можем воплотить в жизнь любые варианты. Классические кухни. Это грамотный тандем простоты,
          строгости и изящества. Здесь нет лишних деталей, а каждый элемент находится на своем месте. Натуральные
          материалы благородных тонов и качественная фурнитура направлены на создание уюта и гармонии. Современные
          кухни. Это неординарный подход к оформлению интерьера. В стилистике гармонично сочетаются простые формы,
          современные материалы и высокотехнологичное оборудование. Они наполняют помещение комфортом, функциональностью
          и неповторимостью. Вы можете познакомиться с фото наших работ в каталоге на сайте и на странице <a
            target="_blank" href="https://www.instagram.com/jmebel06/?igsh=MTZ2dWkzcDM4N21hbg%3D%3D">instagram</a>.
          Заполните форму
          обратной связи, и наши специалисты свяжутся с вами для обсуждения условий заказа.</p>
      </div>
    </div>
  </div>
  <div class="conteiner_about">
    <div class="baner_about">
      <div class="front_content">
        <h3>
          Наша продукция
        </h3>
        <p>Включает в себя широкий ассортимент мебели для гостиной, спальни, кухни и офиса, а также аксессуары и
          элементы декора, чтобы сделать ваш дом полноценным и уютным. Присоединяйтесь к нам в путешествии по миру
          мебели Jmebel и давайте вместе создадим пространство, которое будет вдохновлять и утешать вас каждый день.</p>
      </div>
      <img src="/img-logo/Gallere_neo/n12.jpg" alt="">
    </div>
  </div>
  <div class="about2">
    <h1>Jmebel - ваш дом, ваш стиль, наша мебель.</h1>
  </div>
</template>

<style>
body {
  background-color: black;
  /* display: flex;
  justify-content: center;
  align-items: center;
  min-height: 100hp; */
}

.conteiner_about {
  margin: 152px auto;
  width: 70%;

}

.about2 h1 {
  color: #fdc200;
  font-size: 43px;
  line-height: 43px;
  text-transform: uppercase;
  letter-spacing: 0.6px;
  text-align: center;
  margin-bottom: 100px;
}

.about h2 {
  color: #fdc200;
  font-size: 43px;
  line-height: 43px;
  text-transform: uppercase;
  letter-spacing: 0.6px;
  text-align: center;
  margin-bottom: 50px;
  /* margin: 0 0 50% 45%; */
}

.about h3 {
  color: #fdc200;
  font-size: 43px;
  line-height: 43px;
  text-transform: uppercase;
  letter-spacing: 0.6px;
  text-align: center;
}

.front_content {
  /* margin: 0 592px 0 0; */
  padding: 35px 0 0 0;
  line-height: 23px;
  text-align: right;
}

.front_content a {
  color: orange;
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
  max-width: 490px;
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

/* @media (min-width: 1024px) {
  
} */

@media (max-width: 905px) {
  .conteiner_about .baner_about {
    flex-direction: column;
    display: flex;
    align-items: center;
    margin-bottom: 25px;
  }

  .conteiner_about {
    margin: 50px;
  }

  .about h3 {
    font-size: 27px;
  }
  .about h2 {
    font-size: 35px;
  }

  .front_content {
    text-align: center;
    max-width: 127%;
  }

  .baner_about img {
    max-width: 127%;
  }
}
</style>
