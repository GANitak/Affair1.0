<template>
  <img alt="Face" src="./assets/Face.jpeg" width="350px" height="450px" />
  <Home msg="Welcome to GANitak's portal" />
</template>

<script>
import Home from "./components/Home.vue";

export default {
  name: "App",
  components: {
    Home,
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
#h1{
  font-family: serif;
}
</style>
