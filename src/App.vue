<template>
  <div id="app">
    <div class="w-[1080px] h-[100px] bg-[cyan]">
      头部内容
    </div>


    <h1>sad</h1>
    <h3>这个是dev分支(陈开阳)</h3>
    <h3>陈开阳的第一次测试(功能2)</h3>
    <h3>正能量啊正能量(安俊涛)</h3>
    <h1 class="bg">这是完美无BUG低功耗优美UI的超级-- 功能1(张傲宇)</h1>
    <p>这是关于我给张宝其的自我介绍,我叫张宝其，我是个秒男,八秒真男人,第九秒就不行了(王家轩)</p>
    
    <h3>我叫张宝奇</h3>
<<<<<<< HEAD
    <div class="add">
      <button @click="dianji">我是中间的第三个div,请点我(王家轩)</button>
    </div>
=======
    <section>
      <div id="one" class="bg-[red] h-[15vw]">
        中间的第一个div
      </div>
    </section>

    <div class="add">
      <button @click="dianji">我是中间的第三个div,请点我(王家轩)</button>
>>>>>>> 32bd18823d29c6ad2222893e7e4ee3a00e281bbe
    <div class="miffle_Tew">
        <h3>招商面板</h3>
        <p>这是页面中间内容第三块</p>
    </div>
      <button @click="dianji">我是中间的第三个div,请点我(王家轩)</button>
      <div class="miffle_Tew">
          <h3>招商面板</h3>
          <p>这是页面中间内容第三块</p>
      </div>
  </div>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
  },
  methods: {
    dianji(){
      alert("暗区突围,启动!")
    }
  }
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
.miffle_Tew {
  background: #fff;
  padding: 10px;
  margin: 10px;
  border: 1px solid #ccc;
  border-radius: 5px;
}
.miffle_Tew h3 {
  background: #000;
  color: #fff;
  padding: 5px;
  margin: 0;
}
</style>
