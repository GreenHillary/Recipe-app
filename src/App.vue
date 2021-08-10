<template>
  <div id="app">
    <RecipeTile msg="Welcome to the recipe list!"/>
  </div>
</template>

<script>
import RecipeTile from './components/RecipeTile.vue'

export default {
  name: 'App',
  components: {
    RecipeTile
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
