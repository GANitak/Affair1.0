<template>
  <img alt="Face" src="./assets/IMGanit.svg" />
  <Home msg="Welcome to GANitak's portal" />
<body>
    <h1>Here is the 1st STAGE 1.0</h1>
    <title>Affair 1.☻</title>
<h2>What's up humans 🤠?!</h2>
<h2>Music is happening 🎻</h2>
<!-- <a href="https://ganitak.io" target="_blank" rel="link2site" -->
        <!-- > <button @click="gotoGANitak()">GANitak.io</button> ⤖ landing app</a>. -->
    <h3>Eco🍀system</h3>
Earth, Species🕊, Love&#128149;


<input v-model="message" placeholder="call me back" />
<p>Message is: {{ message }}</p>


    <div id="app"></div>
    <!-- built files will be auto injected -->
  </body>

</template>

<script>
import Home from "./components/Home.vue";
//import GANitak from "./components/GANitak.vue";

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
