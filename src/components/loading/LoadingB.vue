<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2022-04-15 09:07:47
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 09:12:14
-->
<template>
    <div>
        <div class="progress-2"></div>
    </div>
</template>

<script>
    export default {
    
    }
</script>

<style lang="scss" scoped>
* {
    box-sizing: border-box;
}
.progress-2 {
    width: 120px;
    height: 20px;
    border-radius: 20px;
    background: linear-gradient(orange 0 0) 0/0% no-repeat lightblue;
    animation: p2 2s infinite steps(10);
}
@keyframes p2 {
    100% {
        background-size: 110%;
    }
}
</style>