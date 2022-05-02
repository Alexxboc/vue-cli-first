<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" /> -->
    <MyTitle/>
    <heroImage/>
  </div>
</template>

<script>
import MyTitle from "./components/title.vue";
import heroImage from "./components/hero.vue"


export default {
  name: 'App',
  components: {
    MyTitle,
    heroImage,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
