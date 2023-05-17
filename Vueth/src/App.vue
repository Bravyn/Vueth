<script setup>
import { RouterLink, RouterView } from 'vue-router'

</script>

<template>
  <div class = "container">
  <header>   
  <div>
      <nav>
        <div class = "logo">
          <img alt="Vue logo" class="logo" src="@/assets/logo.svg" width="125" height="125" />
        </div>
        
          <RouterLink to="/">Home</RouterLink>
  
          <RouterLink to="/about">About</RouterLink>
      
          <div >
            <h1><span>Vueth</span> Labs</h1>
          </div>
        </nav>
      
    </div>
  </header>
 
</div>
  
    <RouterView />   
  

</template>

<style>
.container{
  display: flex;
  flex-wrap: wrap;
  flex-direction: column;
  justify-content: space-around;
  
}
h1{
  color: white;
}

nav{
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  background-color: grey;
  color: white;
  font-size: 16px;
  font-weight: bold;
}

h1{
  color: blue;
}
</style>