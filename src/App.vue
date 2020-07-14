<template>
  <div id="app" class="--max-width-1280">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link>
    </div> -->
    <router-view/>
  </div>
</template>

<script>
import './assets/css/app.css'
export default {
  
}
</script>
<style scoped>

#app{
  padding: 0 2em;
}

@media screen and (min-width: 768px){
    #app{
      padding: 0 4em;
    }
}

/* #nav a.router-link-exact-active {
  color: #42b983;
}  */
</style>
