<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <h3>Vue3 Mathjax</h3>
  <HelloWorld msg="Hello Vue 3 in CodeSandbox!" />
</template>

<script>
import HelloWorldVue from "./components/HelloWorld.vue";
export default {
  name: "App",
  components: {
    HelloWorld: HelloWorldVue,
  },
};
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
