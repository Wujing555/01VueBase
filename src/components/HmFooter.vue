<template>
    <div class="hm-footer">
        我是hm-footer
        <HmButton></HmButton>
    </div>

</template>

<script>
import HmButton from './HmButton.vue';

export default {
    components: { HmButton }
}
</script>

<style  scoped>
.hm-footer{
    height: 100px;
    line-height: 100px;
    text-align: center;
    font-size: 30px;
    background-color: #084eb7;
    color: white;
    margin: 20px;
}

</style>