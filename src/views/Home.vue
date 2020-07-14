<template>
  <div class="home">
    <appHeader></appHeader>
    <main class="app-main">
      <appBanner></appBanner>
      <div class="app-main__app-product-store-wrapper">
        <appProductStore></appProductStore>
      </div>
    </main>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import appHeader from '@/components/app-header.vue'
import appBanner from '@/components/app-banner.vue'
import appProductStore from '@/components/app-product-store.vue'

export default {
  name: 'Home',
  components: {
    appHeader,
    appBanner,
    appProductStore
  }
}
</script>

<style scoped>
  .app-main{
    margin: 3em 0;
  }
</style>
