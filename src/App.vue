<template>
  <div id="app">
    <h1>sad</h1>
    <h3>这个是dev分支(陈开阳)</h3>
    <h3>陈开阳的第一次测试(功能2)</h3>
    <h3>正能量啊正能量(安俊涛)</h3>
    <h1 class="bg">这是完美无BUG低功耗优美UI的超级-- 功能1(张傲宇)</h1>
    <p>这是关于我给张宝其的自我介绍,我叫张宝其，我是个秒男,八秒真男人,第九秒就不行了(王家轩)</p>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
.bg {
  color: yellow;
  background: brown;
}
</style>
