<template>
  <div class="App">
    <HmHeader></HmHeader>
    <HmMain></HmMain>
    <HmFooter></HmFooter>
  </div>
</template>

<script>
import HmHeader from './components/HmHeader.vue'
import HmMain from './components/HmMain.vue'
import HmFooter from './components/HmFooter.vue'

export default { 
  components:{
    // '组件名'：组件对象
    HmHeader:HmHeader,
    HmMain:HmMain,
    HmFooter:HmFooter

  }

}
</script>

<style  scoped>
.App{
  width: 600px;
  height: 700px;
  background-color: #58b1d2;
  margin: auto;
}
</style>