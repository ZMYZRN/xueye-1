<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>
      嘉然小姐的主页
      <a href="https://space.bilibili.com/672328094" target="_blank" rel="noopener">点击这里去当嘉然小姐的狗</a>.
    </p>
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
