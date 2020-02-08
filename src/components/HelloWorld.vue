<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <ul class="wrapper">
      <li class="item"> this is 1 item </li>
      <li class="item"> this is 2 item </li>
      <li class="item"> this is 3 item </li>
      <li class="item"> this is 4 item </li>
      <li class="item"> this is 5 item </li>
    </ul>
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
<style scoped lang="scss">
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
