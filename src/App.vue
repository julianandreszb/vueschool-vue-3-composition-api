<script setup>
import HelloWorld from './components/HelloWorld.vue'
import YummyMeal from "./components/YummyMeal.vue";
import {provide, ref} from "vue";
import Home from "./views/Home.vue";

// const addToCart = name => console.log('addToCart.name', name);
// const refToInject = ref('$$--');

// provide('currencySymbol', refToInject);

</script>

<template>
  <Home></Home>

<!--  <YummyMeal-->
<!--      name="Bandeja Paisa"-->
<!--      :price="Math.trunc(30)"-->
<!--      @addToCart="addToCart"-->
<!--  ></YummyMeal>-->
<!--  <HelloWorld msg="Vite + Vue"/>-->

</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}

.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}

.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style>
