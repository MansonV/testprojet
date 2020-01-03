<template>
  <div id="app">
    <img src="./assets/logo.png">
    <tagsearch name='counter strike' tag='fps, modern, coop, lan, offline, online' />
  </div>
</template>

<script>
import tagsearch from './components/tagsearch'

export default {
  name: 'App',
  components: {
    tagsearch
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
