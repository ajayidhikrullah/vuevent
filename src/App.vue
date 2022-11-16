<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <eventsView msg="Welcome to Your Events View App"/>
</template>

<script>
import eventsView from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    eventsView
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
