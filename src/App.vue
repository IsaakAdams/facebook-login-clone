<template>
  <div id="app">
    <MainContent />
  </div>
</template>

<script>
import MainContent from './components/MainContent.vue';

export default {
  name: 'App',
  components: {
    MainContent
  }
}
</script>

<style scoped>
  * {
    box-sizing: border-box;
  }
  
  #app {
    font-family: 'Roboto, Segoe UI';
    background-color: #f0f2f5;
  }
</style>