<template>
<!-- //adding components into the div -->
  <div id="app"> 
    <MyHeader/>
    <MyBody/>
    <MyFooter/>
  </div>
</template>

<script>
//importing my components
import MyHeader from "./components/MyHeader.vue"
import MyFooter from "./components/MyFooter.vue"
import MyBody from "./components/MyBody.vue"

export default {
  name: 'App',
  components: {
    MyHeader,
    MyFooter,
    MyBody  //declaring my components as part of app
  }
}
</script>

<style>
//removing default styling
* { 
  margin:0;
  padding:0;
  box-sizing:border-box;
}
html {
  background-color:grey;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
