<script setup>
defineProps({
  msg: {
    type: String,
    required: true
  }
})
</script>

<template>
  <div>
  <div class="welcome">
    <h1>{{ msg }}</h1>
    <h3>
     Login
    </h3>
  </div>
  </div>
</template>

<style scoped>


</style>