<template>
  <div id="screen" class="screen">
    <div class="item">1</div>
    <div class="item">2</div>
    <div class="item">3</div>
    <div class="item">4</div>
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
.item{
  float: left;
  width: 960px;
  height: 540px;
  background-color: green;
  font-size: 200px;
  color: white;
}
.item:nth-of-type(1){
  background-color: gold;
}
.item:nth-of-type(2){
  background-color: red;
}
.item:nth-of-type(3){
  background-color: blue;
}
</style>
