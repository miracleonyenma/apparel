<template>
  <section class="app-banner">
      <img class="app-banner__img" :src="appBanner__img.src" :alt="appBanner__img.alt">
      <header class="app-banner__header">
          <h1>$20 OFF YOUR FIRST PURCHASE, PLUS A DISCOUTED DELIVERY!</h1>
          <p>On all new arrivals</p>
      </header>
  </section>
</template>

<script>
import '@/assets/css/app-banner.css'
export default {
    name: 'app-banner',
    data(){
        return{
            appBanner__img: {
                src: require("../assets/img/model3.jpg"),
                alt: "A pic of a model"
            }
        }
    }
}
</script>

<style scoped>
</style>