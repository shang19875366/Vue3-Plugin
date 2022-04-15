<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2022-04-15 10:57:05
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 10:57:06
-->
<template>
    <div>
        <div class="progress-8"></div>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
* {
    box-sizing: border-box;
}
.progress-8 {
    width: 60px;
    height: 60px;
    border-radius: 50%;
    -webkit-mask: linear-gradient(0deg, #000 55%, #0000 0) bottom/100% 18.18%;
    background: linear-gradient(#f03355 0 0) bottom/100% 0% no-repeat #ddd;
    animation: p8 2s infinite steps(7);
}
@keyframes p8 {
    100% {
        background-size: 100% 115%;
    }
}
</style>