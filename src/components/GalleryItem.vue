<template>
    <div class="img_conteiner">
        <div class="mod_img">
            <div class="img" v-for="imgSrc in imgSources" :key="imgSrc" @click="openPopup(imgSrc)">
                <img :src="imgSrc" alt="">
            </div>
        </div>
        <div v-if="isShowPopup" class="pop_up">
            <span @click="hidePopup()">&times;</span>
            <img :src="imgSrc" alt="">
        </div>
    </div>
</template>

<style>
.img_conteiner .mod_img {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-wrap: wrap;
  gap: 10px;
  margin-bottom: 10px;
}

.img_conteiner .mod_img .img {
  width: 350px;
  height: 250px;
  border: 5px solid #fdc200;
}

.img_conteiner .mod_img .img img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  cursor: pointer;
  transition: .5s;
}

.img_conteiner .mod_img .img:hover img {
  transform: scale(1.1);
}

.img_conteiner .pop_up {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 0, .8);
  /* display: none; */
}

.img_conteiner .pop_up img {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  border: 5px solid #fdc200;
  border-radius: 8px;
  max-width: 100%;
  max-height: 100%;
}

.img_conteiner .pop_up span {
  position: fixed;
  top: 10px;
  right: 20px;
  width: 40px;
  height: 40px;
  background: #ff8c00;
  font-size: 50px;
  font-weight: 900;
  text-align: center;
  line-height: 40px;
  cursor: pointer;
}
</style>

<script>

export default {

        props: {
          imgSources: {
            type: Array,
            default: () => []
          },
        },
        data() {
            return {
                isShowPopup: false,
                imgSrc: ''
            }
        },
        methods: {
            openPopup(imgSrc) {
                this.isShowPopup = true
                this.imgSrc = imgSrc
            },
            hidePopup() {
                this.isShowPopup = false
            }
        }
    }

</script>