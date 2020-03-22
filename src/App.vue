<template>
  <div id="app">
    <loading-screen :is-loading="isLoading"></loading-screen>
    <!-- <img alt="Vue logo" src="./assets/logo.png" /> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <Portfolio/>
  </div>
</template>

<script>
import Loader from "./components/Loader";
import HelloWorld from "./components/HelloWorld.vue";
import Portfolio from "./components/Portfolio.vue";

export default {
  name: "App",
  components: {
    Portfolio,
    "loading-screen": Loader
  },
    data() {
    return {
      isLoading: true
    }
  },
  mounted () {
    setTimeout(() => {
      this.isLoading = false
    }, 4000)
  }
};
</script>

<style>
@import './../node_modules/bulma/css/bulma.css';
@import url('https://fonts.googleapis.com/css?family=IBM+Plex+Mono|Patrick+Hand|Press+Start+2P|Quantico&display=swap');
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */
</style>