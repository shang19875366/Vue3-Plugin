<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2022-04-15 10:48:30
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 10:51:01
-->
<template>
    <div>
        <div class="progress-4"></div>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
* {
    box-sizing: border-box;
}
.progress-4 {
    width: 120px;
    height: 20px;
    -webkit-mask: linear-gradient(90deg, #000 70%, #0000 0) 0/20%;
    background: linear-gradient(#000 0 0) 0/0% no-repeat #ddd;
    animation: p4 2s infinite steps(6);
}
@keyframes p4 {
    100% {background-size:120%}
}
</style>