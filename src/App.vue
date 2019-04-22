<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Main />
  </div>
</template>

<script>
import Main from './main/Main.vue'

export default {
  name: 'app',
  components: {
    Main
  }
}
</script>

<style>
  body {
    font-family: Helvetica, sans-serif;
  }
</style>

