<template>
    <div class="hm-header">
        我是hm-header
        <HmButton></HmButton>
        </div>
</template>

<script>
//局部注册  只能在当前组件范围内使用
// import HmButton from './HmButton.vue'
export default { 

    // components:{
    //     HmButton
    // }
}
</script>

<style  scoped>
.hm-header{
    height: 100px;
    line-height: 100px;
    text-align: center;
    font-size: 30px;
    background-color: #804c80;
    color: white;
}

</style>