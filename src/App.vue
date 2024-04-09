<template>
  <div id="app">
    <AppTitle />
    <Jumbotron />
  </div>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import Jumbotron from './components/Jumbotron.vue';
  export default {
    name: 'App',
  components: {
    AppTitle,
    Jumbotron
  },
};
</script>

<style scoped>

</style>