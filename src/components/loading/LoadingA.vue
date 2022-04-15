<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2022-04-14 16:28:40
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 10:29:02
-->
<template>
    <div>
        <div class="progress-1"></div>
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
.progress-1 {
    width: 120px;
    height: 20px;
    background: linear-gradient(#000 0 0) 0/0% no-repeat #ddd;
    animation: p1 2s infinite linear;
}
@keyframes p1 {
    100% {
        background-size: 100%;
    }
}
</style>