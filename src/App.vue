<!--
 * @Descripttion: 
 * @version: 0.1.0
 * @Author: szx
 * @Date: 2020-12-11 13:54:50
 * @LastEditors: szx
 * @LastEditTime: 2022-04-15 11:08:28
-->
<template>
    <div id="app">
        <div class="m-flex">
            <loading-a></loading-a>
            <loading-b></loading-b>
            <loading-c></loading-c>
            <loading-d></loading-d>
            <loading-e></loading-e>
            <loading-f></loading-f>
            <loading-g></loading-g>
            <loading-h></loading-h>
            <loading-i></loading-i>
            <loading-j></loading-j>
        </div>

    </div>
</template>

<script>
import LoadingA from "./components/loading/LoadingA.vue";
import LoadingB from "./components/loading/LoadingB.vue";
import LoadingC from "./components/loading/LoadingC.vue";
import LoadingD from "./components/loading/LoadingD.vue";
import LoadingE from "./components/loading/LoadingE.vue";
import LoadingF from "./components/loading/LoadingF.vue";
import LoadingG from "./components/loading/LoadingG.vue";
import LoadingH from "./components/loading/LoadingH.vue";
import LoadingI from "./components/loading/LoadingI.vue";
import LoadingJ from "./components/loading/LoadingJ.vue";
export default {
    components: {
        LoadingA,
        LoadingB,
        LoadingC,
        LoadingD,
        LoadingE,
        LoadingF,
        LoadingG,
        LoadingH,
        LoadingI,
        LoadingJ
    },
    data() {
        return {};
    },
};
</script>

<style lang="scss" scoped>
.m-flex {
  display: flex;
  justify-content: space-around;
  align-items: center;
  flex-wrap: wrap;
}
</style>