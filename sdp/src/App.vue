<template>
  <div id="app" class="ryuk_bg">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
body {
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

.ryuk_bg {
  background-color: #2c3e50;
  background-color: rgba(0, 0, 0);
  background-image:url(./assets/life.png);
  width: 100vw;
  height: 100vh;
  position: relative;
  overflow: hidden;
  background-size: contain;
  background-repeat: no-repeat;
  background-position: center center;
  background-attachment: fixed;
}
</style>
