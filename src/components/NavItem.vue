<template>
  <div class="wrapper">
    <div :class="['head', color]">
      <div class="logo">
        <a class="header_logo" href="/">
          <img src="/img-logo/Logo-removebg-preview.png" alt="Kropp Logo" class="header_logo_image">
        </a>
      </div>
      <div class="item">
        <button class="burger" @click="burgerToggle">
          <span class="bar bar1"></span>
          <span class="bar bar2"></span>
          <span class="bar bar1"></span>
        </button>
        <nav class="header-menu" :class="{ 'active': menuOpen }">
          <ul class="header-menu-list">
            <li class="header-menu-item">
              <a class="header-menu-link" href="/">Главная</a>
            </li>
            <li class="header-menu-item">
              <a class="header-menu-link" href="/about">О нас</a>
            </li>
            <li class="header-menu-item">
              <a class="header-menu-link" href="/blog">Блог</a>
            </li>
            <li class="header-menu-item">
              <a class="header-menu-link" href="/galeri">Галерея</a>
            </li>
          </ul>

          <button class="close" @click="closeMenu">
            <div class="sign"><svg viewBox="0 0 512 512">
                <path
                  d="M377.9 105.9L500.7 228.7c7.2 7.2 11.3 17.1 11.3 27.3s-4.1 20.1-11.3 27.3L377.9 406.1c-6.4 6.4-15 9.9-24 9.9c-18.7 0-33.9-15.2-33.9-33.9l0-62.1-128 0c-17.7 0-32-14.3-32-32l0-64c0-17.7 14.3-32 32-32l128 0 0-62.1c0-18.7 15.2-33.9 33.9-33.9c9 0 17.6 3.6 24 9.9zM160 96L96 96c-17.7 0-32 14.3-32 32l0 256c0 17.7 14.3 32 32 32l64 0c17.7 0 32 14.3 32 32s-14.3 32-32 32l-64 0c-53 0-96-43-96-96L0 128C0 75 43 32 96 32l64 0c17.7 0 32 14.3 32 32s-14.3 32-32 32z">
                </path>
              </svg></div>

            <div class="text1">Закрыть меню</div>
          </button>
        </nav>
        <div class="phone">
          <a href="tel:+77716419516">+7 771 641 95 16</a>
          <span>Ежедневно 10:00 до 19:00</span>
        </div>
        <div class="buttn">
          <div class="but-int">
            <a href="https://www.instagram.com/jmebel06?igsh=MTZ2dWkzcDM4N21hbg==" target="_blank">
              <button class="Btn">
                <span class="svgContainer">
                  <svg fill="white" class="svgIcon" viewBox="0 0 448 512" height="1.5em"
                    xmlns="http://www.w3.org/2000/svg">
                    <path
                      d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z">
                    </path>
                  </svg>
                </span>
                <span class="BG"></span>
              </button>
            </a>
          </div>
          <a href="https://www.tiktok.com/@jmebel_06?_t=8nXvqtmpPdd&_r=1" target="_blank">
          <button class="Btn-tt">
            <span class="svgContainer-tt">
              <svg viewBox="0 0 19.738 22.466" height="22.466" width="19.738" xmlns="http://www.w3.org/2000/svg"
                data-name="Group 101" id="Group_101">
                <path fill="#000" transform="translate(-31.423 -0.39)"
                  d="M51.151,6.015a5.661,5.661,0,0,1-3.42-1.143A5.662,5.662,0,0,1,45.469.39H41.8V10.414l0,5.49a3.325,3.325,0,1,1-2.281-3.151V9.029a7.218,7.218,0,0,0-1.058-.078,7.034,7.034,0,0,0-5.286,2.364,6.893,6.893,0,0,0,.311,9.505,7.158,7.158,0,0,0,.663.579,7.035,7.035,0,0,0,4.312,1.458,7.219,7.219,0,0,0,1.058-.078,7.011,7.011,0,0,0,3.917-1.959,6.868,6.868,0,0,0,2.06-4.887l-.019-8.2a9.3,9.3,0,0,0,5.688,1.933V6.014h-.011Z"
                  data-name="Path 6566" id="Path_6566"></path>
              </svg>
            </span>
            <span class="BG-tt"></span>
          </button>
        </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.burger {
  display: none;
  position: relative;
  z-index: 50;
  align-items: center;
  justify-content: flex-end;
  width: 30px;
  height: 18px;
}

.close {
  display: none;
}

.header-menu {
  transition: all linear .3s;
  /* box-sizing: border-box; */
}

.header-menu ul li a {
  /* display: block; */
  margin: 50px 0 0 0;
  padding: 0 0 0 0;
  border-bottom: 3px solid #fdc200;
  font-weight: 500;
  text-transform: uppercase;
  letter-spacing: 0.4px;
  text-decoration: none;
  font-size: 13px;
}

.header-menu ul li a:hover {
  border-bottom: 3px solid black;
}

.Btn-tt {
  width: 45px;
  height: 45px;
  display: flex;
  align-items: center;
  justify-content: center;
  border: none;
  background-color: transparent;
  position: relative;
  /* overflow: hidden; */
  border-radius: 7px;
  cursor: pointer;
  transition: all .3s;
}

.svgContainer-tt {
  width: 100%;
  height: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  background-color: transparent;
  backdrop-filter: blur(4px);
  letter-spacing: 0.8px;
  border-radius: 10px;
  transition: all .3s;
  border: 1px solid rgba(137, 136, 136, 0.466);
}

.BG-tt {
  position: absolute;
  content: "";
  width: 100%;
  height: 100%;
  background: #000000;
  background: -moz-linear-gradient(45deg, #000000 0%, #000000 25%, #000000 50%, #000000 75%, #000000 100%);
  background: -webkit-linear-gradient(45deg, #000000 0%,#02fdfd 25%,#dc2743 50%,#dc2743 75%,#000000 100%);
  background: linear-gradient(45deg, #02fdfd 0%#02fdfd 25%,#02fdfd 50%,#000000 75%,#ffffff 100%);
  filter: progid:DXImageTransform.Microsoft.gradient( startColorstr='#ffffff', endColorstr='#bc1888',GradientType=1 );
  z-index: -1;
  border-radius: 9px;
  pointer-events: none;
  transition: all .3s;
}

.Btn-tt:hover .BG-tt {
  transform: rotate(35deg);
  transform-origin: bottom;
}

.Btn-tt:hover .svgContainer-tt {
  background-color: rgba(214, 211, 209, 0.466);
}


@media (max-width: 905px) {
  .burger {
    display: flex
  }

  .close {
    display: flex;
  }

  .logo {
    margin: -67px;
  }

  .header-menu {
    display: none;
    margin-right: -300px;
    background: #000000;
    justify-content: end;
    position: fixed;
    height: 100%;
    width: 235px;
    top: 0;
    bottom: 0;
    right: 0;
    z-index: 50;
    overflow-y: auto;
    padding: 50px 40px;
    border-color: black;

  }

  .header-menu-list {
    flex-direction: column;
    gap: 15px;
    margin-right: 38px;
  }

  .close {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    width: 45px;
    height: 45px;
    border: none;
    border-radius: 50%;
    cursor: pointer;
    position: relative;
    overflow: hidden;
    transition-duration: .3s;
    box-shadow: 2px 2px 10px rgba(0, 0, 0, 0.199);
    background-color: #fdc200;
  }


  .sign {
    width: 100%;
    transition-duration: .3s;
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .sign svg {
    width: 17px;
  }

  .sign svg path {
    fill: white;
  }

  .text1 {
    position: absolute;
    right: 0%;
    width: 0%;
    opacity: 0;
    color: white;
    font-size: 1.2em;
    font-weight: 600;
    transition-duration: .3s;
  }

  .close:hover {
    width: 125px;
    border-radius: 40px;
    transition-duration: .3s;
  }

  .close:hover .sign {
    width: 30%;
    transition-duration: .3s;
    padding-left: 20px;
  }

  .close:hover .text1 {
    opacity: 1;
    width: 70%;
    transition-duration: .3s;
    padding-right: 10px;
  }

  .close:active {
    transform: translate(2px, 2px);
  }

  .burger {
    width: 45px;
    height: 45px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 6px;
    background-color: #fdc200;
    border-radius: 10px;
    cursor: pointer;
    border: none;
    box-shadow: 0px 0px 0px 2px rgb(255, 255, 255);
  }

  .bar {
    width: 50%;
    height: 2px;
    background-color: rgb(255, 255, 255);
    display: flex;
    align-items: center;
    justify-content: center;
    position: relative;
    border-radius: 2px;
  }

  .bar::before {
    content: "";
    width: 2px;
    height: 2px;
    background-color: #fdc200;
    position: absolute;
    border-radius: 50%;
    border: 2px solid #f9c702;
    transition: all 0.3s;
    box-shadow: 0px 0px 5px #000000;
  }

  .bar1::before {
    transform: translateX(-4px);
  }

  .bar2::before {
    transform: translateX(4px);
  }

  .burger:hover .bar1::before {
    transform: translateX(4px);
  }

  .burger:hover .bar2::before {
    transform: translateX(-4px);
  }

  .buttn{
    display: flex;
    flex-direction: row-reverse;
  }

  .Btn-tt{
    margin: 0px 25px 0;
  }
}
</style>

<script>
// document.querySelector('.burger').addEventListener('click',function(){
//   this.classList.toggle('.active');
//   document.querySelector('.nav').classList.toggle('open');
// })



export default {
  props: {
    color: {
      type: String,
      default: 'dark'
    },
  },
  // data() {
  //   return {
  //     menuOpen: false
  //   };
  // },
  methods: {
    burgerToggle() {
      // document.querySelector('.burger').style.display = 'none';
      document.querySelector('.header-menu').style.display = 'flex';
      setTimeout(() => {
        document.querySelector('.header-menu').style.marginRight = '0';
      }, 100)

    },
    closeMenu() {
      document.querySelector('.header-menu').style.marginRight = '-300px';
      setTimeout(() => {
        // document.querySelector('.burger').style.display = 'flex';
        document.querySelector('.header-menu').style.display = 'none';
      }, 300)
    }
  },
  // toggleMenu() {
  //     this.menuOpen = !this.menuOpen; // Изменяем состояние меню
  //   },
  //   closeMenu() {
  //     this.menuOpen = false; // Закрываем меню
  //   }
}

</script>