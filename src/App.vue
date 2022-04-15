<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <MyHeader/>
    <MyBody/>
    <MyFooter/>
  </div>
</template>

<script>

import MyHeader from "./components/MyHeader.vue"
import MyFooter from "./components/MyFooter.vue"
import MyBody from "./components/MyBody.vue"

export default {
  name: 'App',
  components: {
    MyHeader,
    MyFooter,
    MyBody
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
  background-color: grey;
}
</style>
