<template>
  <div id="GANitak">
    <button @click="gotoGANitak()">GANitak.io</button>
  </div>
</template>

<script>
import GANitak from "./components/GANitak.vue";

export default {
  name: "GANitak",
  methods: {
    gotoGANitak() {
      window.open("https://www.ganitak.io/");
    },
  },
};
</script>

//