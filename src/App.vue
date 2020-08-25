<template>
  <div class="" id="app">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <alert-pop-up></alert-pop-up>
    <app-nav-bar></app-nav-bar>
    <home-page></home-page>
    <app-footer></app-footer>
  </div>
</template>

<script>
import AlertPopUp from "./components/AlertPopUp.vue";
import AppNavBar from "./components/AppNavBar.vue";
import AppFooter from "./components/AppFooter.vue";
import HomePage from "./components/HomePage.vue";

export default {
  name: "App",
  components: {
    AlertPopUp,
    AppNavBar,
    AppFooter,
    HomePage,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  /* margin-top: 60px; */
}
</style>
