<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2022-04-15 10:55:49
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 10:55:49
-->
<template>
    <div>
        <div class="progress-7"></div>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
* {
    box-sizing: border-box;
}
.progress-7 {
    width: 120px;
    height: 24px;
    -webkit-mask: radial-gradient(circle closest-side, #000 94%, #0000) 0 0/25%
            100%,
        linear-gradient(#000 0 0) center/calc(100% - 12px) calc(100% - 12px)
            no-repeat;
    background: linear-gradient(#25b09b 0 0) 0/0% no-repeat #ddd;
    animation: p7 2s infinite linear;
}
@keyframes p7 {
    100% {
        background-size: 100%;
    }
}
</style>