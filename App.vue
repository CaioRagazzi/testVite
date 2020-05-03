<template>
  <h1>Hello Vite + Vue 3!</h1>
  <p>Edit ./App.vue to t replacement aasdsada</p>
  <p>
    <span>Count is: {{ count }}</span>
    <button @click="count++">increment</button>
    <button @click="count--">decrement</button>
  </p>
</template>

<script>
export default {
  data: () => ({ count: 0 }),
}
</script>

<style scoped>
h1 {
  color: #4e614e;
}

h1, p {
  font-family: Arial, Helvetica, sans-serif;
}
</style>
