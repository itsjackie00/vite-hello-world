<template>
    <h1>{{title}}</h1>
  </template>

<script>
  export default {
    name: 'AppTitle',
    data(){
      return {
        title: 'La mia prima app con Vite!'
      }
    }
  };
</script>

<style scoped>
h1 {
    color: red;
    text-align: center;
    margin-bottom: 5rem;
}
</style>