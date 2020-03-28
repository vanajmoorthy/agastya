<template>
  <div class="hello">
    <img alt="Vue logo" src="../assets/aggsu.jpg" />
    <h1>{{ msg }}</h1>
    <p>
      My name is Agastya
    </p>

    <h3>mytoutubechannel</h3>
    <a
      href="https://www.youtube.com/watch?v=dQw4w9WgXcQ"
      target="_blank"
      rel="noopener"
      >i agastya</a
    >
  </div>
</template>

<script>
export default {
  name: "AggsuComp",
  props: {
    msg: String
  }
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  border-radius: 50%;
}
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
