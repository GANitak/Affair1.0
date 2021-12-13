<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      For a guide and recipes on how to configure / customize this project,<br />
      check out the
      <a href="https://cli.vuejs.org" target="_blank" rel="noopener"
        >vue-cli documentation</a
      >.
    </p>
    <h3>How do you feel?</h3>
    <h5>Tell you that i love you!</h5><br>
    <h6>...We can go on forever...</h6>
    <ul>
      <li>
        <a
          href="https://github.com/GANitak/Affair1.0.git"
          target="_blank"
          rel="noopener"
          >Affair1.0</a
        >
      </li>
      <li>
        <a href="https://twitter.com/GANit_ak" target="_blank" rel="noopener"
          >insert clickable svgIcon_Twitter</a
        >
      </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
