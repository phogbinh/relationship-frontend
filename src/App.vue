<template>
  <div id='app'>
    <TheSearch />
  </div>
</template>

<script>
import TheSearch from './components/TheSearch.vue'

export default {
  'name': 'App',
  'components': {
    TheSearch
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
