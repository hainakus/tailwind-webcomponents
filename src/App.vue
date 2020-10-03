<template>
  <div id="app">
    <CardStandard/>
  </div>
</template>

<script>
import CardStandard from './components/card-standard/card-standard.vue'

export default {
  name: 'App',
  components: {
    CardStandard
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
