<template>
  <div id="app">
  
    <HelloWorld/>
    <hr>
    <h1 class="my-4">Nuestros productos</h1>
    <hr>
    <Body/>
 
  </div>
</template>

<script>
import Body from './components/body.vue'
import HelloWorld from './components/HelloWorld.vue'


export default {
  name: 'App',
  components: {
    HelloWorld,
    Body
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
  margin-top: 0px;
}
</style>
