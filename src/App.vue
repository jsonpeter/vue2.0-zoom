<template>
  <div id="app">
    <div class="img-con">
      <img-zoom src="src/img/img-samll.png" bigsrc="src/img/img-big.jpg" ></img-zoom>
    </div>
    <div class="img-con2">
      <img-zoom src="src/img/img-samll.png" width="450" height="250" bigsrc="src/img/img-big.jpg" :configs="configs"></img-zoom>
    </div>
  </div>
</template>

<script>
  import imgZoom from './imgZoom.vue';
export default {
  name: 'app',
  data () {
    return {
      configs: {
        width:650,
        height:350,
        maskWidth:100,
        maskHeight:100,
        maskColor:'red',
        maskOpacity:0.2
      }
    }
  },
  components:{
    imgZoom
  }
}
</script>

<style lang="scss">
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 10px;
}
.img-con{border: 1px solid #ccc; text-align: center; padding:0;}
.img-con2{border: 1px solid #bbb; text-align: center; float: left; margin-top: 20px;}
</style>
