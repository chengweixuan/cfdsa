<template>
  <img src="../assets/logo.png" />
  <br />

  <a href="https://github.com/chengweixuan/cfdsa">link</a>

  <br />
  <div class="hello">
    <h1>{{ msg }}</h1>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
  computed: {
    msg() {
      const random = Math.floor(Math.random() * 5);
      switch (random) {
        case 0:
          return " Logic will get you from A to B. Imagination will take you everywhere.";
        case 1:
          return "There are 10 kinds of people. Those who know binary and those who dont.";
        case 2:
          return "There are two ways of constructing a software design. One way is to make it so simple that there are obviously no deficiencies and the other is to make it so complicated that there are no obvious deficiencies.";
        case 3:
          return "It's not that I'm so smart, it's just that I stay with problems longer.";
        case 4:
          return "It is pitch dark. You are likely to be eaten by a grue.";
        default:
          return "wrong text";
      }
    },
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
