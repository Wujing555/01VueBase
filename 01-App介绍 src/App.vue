<template>
  <div class="App">
    <div class="box" @click="fn">我是元素</div>
  </div>
</template>

<script>
export default { 
  methods:{
    fn(){
      alert('你好')
    }
  }
   
}
</script>

<style  lang="less" scoped>
.App{
  width: 400px;
  height: 400px;
  background-color: bisque;
  .box{
  width: 100px;
  height: 100px;
  background-color:aquamarine;
}
}


</style>