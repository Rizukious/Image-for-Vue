<template>
  <div id="app">
    <Logoos />
  </div>
</template>

<script>
// mengimport file Logoos.vue kedalam App.vue
import Logoos from './components/Logoos.vue'

export default {
  name: 'App',
  components: {
    Logoos
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
