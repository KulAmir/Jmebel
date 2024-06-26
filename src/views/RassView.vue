<script>
import NavItem from '../components/NavItem.vue'

export default {
  components: { NavItem }
}
</script>

<template>
  <NavItem />

  <div class="ras_info">
    <div class="ras_abaut">
      <h3>Хотите обновить интерьер, но не хватает средств на мебель? </h3>
      <h2>Теперь у вас есть отличная возможность приобрести корпусную мебель от Jmebel в рассрочку через наших партнеров
        - банков второго уровня </h2>
    </div>
    <div class="ras_img">
      <img src="/img-logo/Halyk bank.png" alt="">
      <img src="/img-logo/Home bank.png" alt="">
      <img src="/img-logo/Kaspi bank.png" alt="">
    </div>
    <dav class="ras_end">
      <h1>Мы стремимся сделать вашу мебельную покупку максимально удобной и доступной. Подробности уточняйте у наших
        менеджеров или на сайте. Создайте свой идеальный дом без лишних финансовых забот с Jmebel!"</h1>
    </dav>
    <div class="ras_btn">
      <a href="https://api.whatsapp.com/send/?phone=77716419516&text&type=phone_number&app_absent=0" target="_blank">
        <button>Связатся с нами</button></a>
    </div>
  </div>

</template>

<style>
body {
  background-color: black;
}

.ras_info {
  text-align: center;
}

h3 {
  color: #fdc200;
  font-size: 31px;
  line-height: 110px;
  text-transform: uppercase;
  letter-spacing: 2.6px;
  text-align: center;
  margin-bottom: 25px;
}

h2 {
  color: #fdc200;
  font-size: 35px;
  line-height: 50px;
  text-transform: uppercase;
  letter-spacing: 0.6px;
  text-align: center;
  margin-bottom: 50px;
  margin-left: 135px;
  margin-right: 135px;
}

h1 {
  color: #fdc200;
  font-size: 40px;
  line-height: 50px;
  text-transform: uppercase;
  letter-spacing: 0.6px;
  text-align: center;
  margin-bottom: 50px;
  margin-left: 135px;
  margin-right: 135px;
}

.ras_info img {
  margin-right: 200px;
  max-width: 209px;
  float: right;
  border: 6px solid #fdc200;
  border-radius: 60px;
  margin-left: 31px;
  margin-bottom: 60px;
}

.ras_info button {
  text-decoration: none;
  position: relative;
  border: none;
  font-size: 23px;
  font-family: inherit;
  cursor: pointer;
  color: #fff;
  width: 9em;
  height: 3em;
  line-height: 2em;
  text-align: center;
  background: linear-gradient(90deg, #fdd759, #9f7a00, #ffeb3b, #fdc200);
  background-size: 300%;
  border-radius: 30px;
  z-index: 1;
  margin-bottom: 50px;
}

.ras_info button:hover {
  animation: ani 8s linear infinite;
  border: none;
}

@keyframes ani {
  0% {
    background-position: 0%;
  }

  100% {
    background-position: 400%;
  }
}

.ras_info button:before {
  content: "";
  position: absolute;
  top: -5px;
  left: -5px;
  right: -5px;
  bottom: -5px;
  z-index: -1;
  background: linear-gradient(90deg, #fdd759, #9f7a00, #ffeb3b, #fdc200);
  background-size: 400%;
  border-radius: 35px;
  transition: 1s;
}

.ras_info button:hover::before {
  filter: blur(20px);
}

.ras_info button:active {
  background: linear-gradient(32deg, #fdd759, #9f7a00, #ffeb3b, #fdc200);
}

@media (max-width: 1200px) {
  .ras_info h3 {
    font-size: 20px;
    line-height: 35px;
    margin: 23px 50px 30px;
  }

  .ras_info h2 {
    font-size: 20px;
    line-height: 39px;
    margin: 30px 50px 17px;
  }

  .ras_info h1 {
    font-size: 20px;
    line-height: 39px;
    margin: 25px 20px 45px;
  }

  .ras_info img {
    max-width: 157px;
    margin: auto;
  }

  .ras_img {
    display: flex;
  }
}

@media (max-width: 503px) {
  .ras_img {
    display: flex;
  }
  .ras_info img {
    max-width: 120px;
    margin: auto;
  }
}
</style>