<template>
  <div id="app">
    <Readme />
  </div>
</template>

<script>
import Readme from './components/Readme.vue'

export default {
  name: 'app',
  components: {
    Readme
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
