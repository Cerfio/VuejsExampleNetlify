<template>
  <div class="hello">
    <div>
      <p>TF1</p>
      <p>France 2</p>
      <p>France 3</p>
      <p>France 4</p>
      <p>France 5</p>
      <p>M6</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
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
