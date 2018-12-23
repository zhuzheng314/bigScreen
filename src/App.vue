<template>
  <div id="app">
    <Screen />
  </div>
</template>

<script>
import Screen from './components/Screen.vue'

export default {
  name: 'app',
  components: {
    Screen
  },
  mounted() {
  }
}
</script>

<style>
*{
  margin: 0;
  padding: 0;
}
html, body{
  width: 100%;
  height: 100%;
}
</style>
