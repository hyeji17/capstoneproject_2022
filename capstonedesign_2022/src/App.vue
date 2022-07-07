<template>
  <div>
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <pot-header></pot-header>
    <pot-main></pot-main>
    <pot-footer></pot-footer>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import PotHeader from './components/PotHeader.vue'
import PotMain from './components/PotMain.vue'
import PotFooter from './components/PotFooter.vue'


export default {
  name: 'App',
  components: {
    // HelloWorld,
    PotHeader,
    PotMain,
    PotFooter
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
