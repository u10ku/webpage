<template>

  <HeaderMenu></HeaderMenu>
  <HelloWorld msg="Welcome to Your Vue.js App"/>

</template>

<script>

import HeaderMenu from './components/modules/HeaderMenu.vue';

export default {
  name: 'App',
  components: {
 
    HeaderMenu
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
 
}
</style>
