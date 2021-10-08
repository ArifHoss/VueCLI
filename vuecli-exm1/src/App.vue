<template>
  <div id="app">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MyFirstCOmponent/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import MyFirstCOmponent from "@/components/MyFirstComponent";

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyFirstCOmponent
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
img{
  width: 500px;
  height: 300px;
}
</style>
