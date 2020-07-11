<template>
  <div class="home">
    <appHeader></appHeader>
    <main>
      <!-- <img alt="Vue logo" src="../assets/logo.png">
      <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    </main>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import appHeader from '@/components/app-header.vue'

export default {
  name: 'Home',
  components: {
    appHeader,
    // HelloWorld
  }
}
</script>
