<template>
  <noscript>
    "<strong>
      We're sorry but board-web doesn't work properly without JavaScript enabled.
      Please enable it to continue.
    </strong>"
  </noscript>

  <!-- <HelloWorld msg="Welcome to Your Vue.js App" /> -->
  <OnlineShopping msg="Hello"></OnlineShopping>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import OnlineShopping from './components/OnlineShopping.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    OnlineShopping
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  color: #2c3e50;

  height: 100%;
}

body {
  height: 100%;
  -moz-osx-font-smoothing: grayscale;
  -webkit-font-smoothing: antialiased;
  text-rendering: optimizeLegibility;
  margin: 0;

  padding: 0;
}
</style>
