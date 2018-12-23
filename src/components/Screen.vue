<template>
  <div id="screen" class="screen">
    我是大屏
  </div>
</template>

<script>
import initScreen from '../utils/initScreen'
export default {
  name: 'Screen',
  mounted () {
    initScreen(1920, 1080, 'screen')
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.screen{
  background-color: #a9a9a9;
}
</style>
