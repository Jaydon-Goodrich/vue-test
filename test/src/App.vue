<template>
  <div id="app">
    <MyFirst />
  </div>
</template>

<script>
import MyFirst from './components/MyFirst.vue'

export default {
  name: 'App',
  components: {
    MyFirst
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
