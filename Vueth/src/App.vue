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
            <h1>Login </h1>
          </div>

          <div class = "name">
            <h1><span>Vueth</span>Labs</h1>
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


nav{
  display: flex;
  justify-content: space-evenly;
  align-items: center;
  background-color: grey;
  color: white;
  font-size: 14px;
  font-weight: bold;
}

.name{
  color: rgb(5, 5, 126);
}
.name span{
  color:rgb(168, 232, 5);
}

.logo img{
  height:70px;
}
</style>