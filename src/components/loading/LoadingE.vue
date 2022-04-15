<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2022-04-15 10:52:29
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 10:52:30
-->
<template>
    <div>
        <div class="progress-5"></div>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
* {
    box-sizing: border-box;
}
.progress-5 {
    width: 80px;
    height: 40px;
    border: 2px solid #000;
    padding: 3px;
    background: repeating-linear-gradient(90deg, #000 0 10px, #0000 0 16px) 0/0%
        no-repeat content-box content-box;
    position: relative;
    animation: p5 2s infinite steps(6);
}
.progress-5::before {
    content: "";
    position: absolute;
    top: 50%;
    left: 100%;
    transform: translateY(-50%);
    width: 10px;
    height: 10px;
    border: 2px solid #000;
}
@keyframes p5 {
    100% {
        background-size: 120%;
    }
}
</style>