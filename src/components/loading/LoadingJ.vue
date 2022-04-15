<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2022-04-15 10:59:23
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 10:59:24
-->
<template>
    <div>
        <div class="progress-10"></div>
    </div>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
* {
    box-sizing: border-box;
}
.progress-10 {
    width: 120px;
    height: 60px;
    border-radius: 200px 200px 0 0;
    -webkit-mask: repeating-radial-gradient(
        farthest-side at bottom,
        #0000 0,
        #000 1px 12%,
        #0000 calc(12% + 1px) 20%
    );
    background: radial-gradient(farthest-side at bottom, #514b82 0 95%, #0000 0)
        bottom/0% 0% no-repeat #ddd;
    animation: p10 2s infinite steps(6);
}
@keyframes p10 {
    100% {
        background-size: 120% 120%;
    }
}
</style>