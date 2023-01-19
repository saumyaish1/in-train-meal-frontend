<template>
  <div id="app">
    <MainMenu />
    <router-view></router-view>
    <AppFooter></AppFooter>
  </div>
</template>

<script>
import MainMenu from './components/MainMenu.vue'
import AppFooter from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    MainMenu,
    AppFooter
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
  margin-top: 60px;
  margin: 0;
  padding: 0;
  background-color: #FFEEDB;

  /* 0A1D37 FFBD9B FFD8CC FFEEDB */
}
</style>
