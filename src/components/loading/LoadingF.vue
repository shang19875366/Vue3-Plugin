<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2022-04-15 10:54:06
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 10:55:09
-->
<template>
    <div>
        <div class="progress-6"></div>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
* {
    box-sizing: border-box;
}
.progress-6 {
    width: 120px;
    height: 22px;
    border-radius: 20px;
    color: #514b82;
    border: 2px solid;
    position: relative;
}
.progress-6::before {
    content: "";
    position: absolute;
    margin: 2px;
    inset: 0 100% 0 0;
    border-radius: inherit;
    background: #514b82;
    animation: p6 2s infinite;
}
@keyframes p6 {
    100% {
        inset: 0;
    }
}
</style>