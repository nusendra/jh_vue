<script setup>
import { ref } from 'vue'

const count = ref(0)
</script>

<template>
  <main>
    <h1>Hello, Vue 3!</h1>
    <p>Count: {{ count }}</p>
    <button @click="count++">Increment</button>
    <button @click="count--">Decrement</button>
  </main>
</template>

<style scoped>
main {
  font-family: sans-serif;
  text-align: center;
  margin-top: 4rem;
}

button {
  padding: 0.5rem 1.5rem;
  font-size: 1rem;
  cursor: pointer;
  border-radius: 6px;
  border: 1px solid #ccc;
  background: #42b883;
  color: white;
  margin-top: 1rem;
}

button:hover {
  background: #33a06f;
}
</style>
