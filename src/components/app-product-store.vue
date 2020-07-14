<template>
  <section class="app-product-store">
      <header class="app-product-store__header">
          <h1>{{products.title}}</h1>
          <ul class="app-product-store__categories --lst-none">
              <li class="app-product-store__category" v-for="category in products.categories" :key="category.id">
                  {{category.name}}
              </li>
          </ul>
      </header>
      <section class="app-product-store__gallery">
          <ul class="app-product-store__product-list --lst-none">
              <li class="product-item" v-for="product in products.items" :key="product.id">
                  <div class="product-item__img-cont">
                      <img class="product-item__img" :src="product.img" alt="">
                  </div>
                  <h2 class="product-item__title" >{{product.name}}</h2>
              </li>
          </ul>
      </section>
  </section>
</template>

<script>
import '../assets/css/app-product-store.css'

export default {
    data(){
        return{
            products : {
                title : "footwear",
                items : [
                    {
                        id : "0122",
                        name : "nike sth-max",
                        img : require("../assets/img/model1.jpg")
                    },
                    {
                        id : "0522",
                        name : "nike sth-max",
                        img : require("../assets/img/model2.jpg")
                    },
                    {
                        id : "0422",
                        name : "nike sth-max",
                        img : require("../assets/img/model1.jpg")
                    },
                    {
                        id : "0109",
                        name : "nike sth-max",
                        img : require("../assets/img/model3.jpg")
                    },
                    {
                        id : "0023",
                        name : "nike sth-max",
                        img : require("../assets/img/model2.jpg")
                    }
                ],
                categories: [
                    {
                        id : "0129",
                        name : "sandals"
                    },
                    {
                        id : "0243",
                        name : "sandals"
                    },
                    {
                        id : "0234",
                        name : "sandals"
                    }
                ]
            }
        }
    }
}
</script>

<style>

</style>