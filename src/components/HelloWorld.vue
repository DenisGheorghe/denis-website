<script setup>
import { ref } from 'vue'

defineProps({
  msg: String,
})

const count = ref(0)
</script>

<template>
  <h1>{{ msg }}</h1>
  <h2>Software Developer</h2>
  <a href="https://www.linkedin.com/in/denis-gheorghe/" class="link">
    <img src="../assets/linkedin-logo.svg" class="logo" alt="linkedin logo" />
   <h3>LinkedIn</h3>
  </a>
</template>

<style scoped>

</style>
