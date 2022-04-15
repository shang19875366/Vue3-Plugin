<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2022-04-15 10:33:49
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 10:47:35
-->
<template>
    <div>
        <div class="progress-3"></div>
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
.progress-3 {
    width: 120px;
    height: 20px;
    border-radius: 20px;
    background: repeating-linear-gradient(135deg,#f03355 0 10px, #ffa516 0 20px) 0/0% no-repeat, repeating-linear-gradient(135deg, #ddd 0 10px, #eee 0 20px) 0/100%;
    animation: p3 2s infinite;
}
@keyframes p3 {
    100% {
        background-size: 100%;
    }
}
</style>