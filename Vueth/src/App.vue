<script setup>
import { RouterLink, RouterView } from 'vue-router'
import {NavBar} from './components/NavBar.vue'
</script>

<template>
  <div class = "container">
  <header>
    <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
    <NavBar/>
  </header>
  <div>
    <h1>Vueth Labs</h1>
  </div>
</div>
  
    <RouterView />   
  

</template>

<style>
.container{
  background-color: blue;
  display: flex;
  justify-content: space-around;
}
h1{
  color: white;
}

</style>