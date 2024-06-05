<template>
    <div class="wrapper">
      <div :class="['head', color]">
        <div class="logo">
          <a class="header_logo" href="/">
            <img 
            src="/img-logo/Logo-removebg-preview.png" 
            alt="Kropp Logo" 
            class="header_logo_image">
          </a>
        </div>
        <div class="item">
          <nav class="header-menu">
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
          </nav>
          <div class="phone">
            <a href="tel:+77716419516">+7 771 641 95 16</a>
            <span>Ежедневно 10:00 до 19:00</span>
          </div>
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
        </div>
      </div>
    </div>
</template>

<style>
  /* .head.light {
    background: #fff;
  }

  .head.light a {
    color: #000;
  } */

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
</style>

<script>

export default {
  props: {
    color: {
      type: String,
      default: 'dark'
    },
  }
}

</script>