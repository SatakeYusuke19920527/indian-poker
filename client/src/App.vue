<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <SampleComponent msg="Vue初体験。こんなの初めて❤️"/>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import SampleComponent from './components/SampleComponent.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    SampleComponent
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
}
</style>
