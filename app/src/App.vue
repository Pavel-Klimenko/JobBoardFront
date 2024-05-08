<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Hello World, meet Buddy!"/>
    <br />    <br />    <br />

    <HelloWorld1 msg1="Hello World, meet Buddy!44444"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HelloWorld1 from './components/HelloWorld1.vue'
export default {
  name: 'app',
  components: {
    HelloWorld,
    HelloWorld1
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>