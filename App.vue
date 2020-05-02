<template>
  <h1>Hello Vite + Vue 3!</h1>
  <p>Edit ./App.vue to t replacement aasdsada</p>
  <p>
    <span>Count is: {{ count }}</span>
    <button @click="increment">increment</button>
    <button @click="decrement">decrement</button>
  </p>
</template>

<script>
export default {
  data: () => ({ count: 0 }),
  watch:{
    count(newVal, oldVal){
      console.log(newVal);
      console.log(oldVal);
      
    }
  },
  created(){
    console.log('created');
    
  },
  updated(){
    console.log('updated');
    
  },
  methods: {
    increment(){
      this.count++
    },
    decrement(){
      this.count--
    }
  }
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
