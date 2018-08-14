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
  margin: 20px 60px 0;
}
</style>
