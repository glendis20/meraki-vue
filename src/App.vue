<template>
  <div id="app">
    <CoNav/>
    <CoInicio msg="Meraki" />
    <img id="logo" src="./assets/lotus.png" alt="">
  </div>
</template>

<script>
import CoNav from "./components/CoNav";
import CoInicio from "./components/CoInicio";

export default {
  name: "App",
  components: {
    CoNav,
    CoInicio, 
  },
};
</script>

<style>
*{
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#logo{
  width: 200px;
  height: auto;
}
</style>
