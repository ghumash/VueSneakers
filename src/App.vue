<script setup>
  import { ref } from 'vue'

  let count = ref(0)

  const increment = () => count.value++
</script>

<template>
  <h2>Count: {{ count }}</h2>
  <button @click="increment">+</button>
  <input v-model="count"/>
</template>

<style scoped>

</style>
