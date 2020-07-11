<template>
  <header class="app-header">
      <div class="app-header__wrapper --max-width-1560">
        <figure class="app-logo">
            <h1>APPAREL</h1>
        </figure>
        <div class="app-header__search-cont">
            <input class="app-header__search-input" type="search" name="glabal-search" id="global-search" placeholder="Search items, apparels, clothes">
            <button class="app-header__search-btn">Search</button>
        </div>
        <div class="app-header__actions-cont">
            <div class="app-header__cart">
                <span>cart</span>
            </div>
            <div class="app-header__account">
                <span>account</span>
            </div>
            <div class="app-header__language">
                <span>NG</span>
            </div>
        </div>
      </div>
  </header>
</template>

<script>
import '../assets/css/app-header.css'

export default {
    name: 'app-header'
}
</script>

<style lang="css" scoped>

</style>