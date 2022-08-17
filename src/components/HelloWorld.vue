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

    <div>1 px 边框</div>
    <div class="hairline"></div>
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
h1 {
  font-size: 16px;
  font-weight: 550;
}

a {
  color: #42b983;
  font-size: 14px;
}
p {
  font-size: 16px;
}
.hairline {
  border-top: 1px solid #000;
  width: 100vw;
}
</style>
