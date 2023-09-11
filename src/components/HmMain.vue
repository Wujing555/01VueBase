<template>
    <div class="hm-main">我是hm-main
        <h2>hello vue</h2>
        <button @click="count++">学了{{ count }}次
        </button>
        <HmButton></HmButton>
    </div>
    
</template>

<script>
export default { 

    data(){
        return{
            count:0
        }
    }

}
</script>

<style  scoped>
.hm-main{
    height: 400px;
    line-height: 100px;
    text-align: center;
    font-size: 30px;
    background-color: #d67718;
    color: white;
    margin: 20px;
}

</style>