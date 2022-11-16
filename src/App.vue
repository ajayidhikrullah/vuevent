<template>
  <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
  <eventsView msg="Welcome to Your Events View App"/>
  <contactUs msg="Contact us"/>

</template>

<script>
import eventsView from './components/HelloWorld.vue'
import contactUs from './components/contactUs.vue'


export default {
  name: 'App',
  components: {
    eventsView,
    contactUs
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #723131;
  margin-top: 60px;
}
</style>
