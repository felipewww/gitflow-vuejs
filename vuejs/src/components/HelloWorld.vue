<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>Card #1</p>
    <p>Card #2 - merge commit233</p>
    <p>Card #2 - versão 2.0.0. Deverá ser revertido para cá!</p>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  },
  methods: {
    // v2.0.0
    fake: () => {
      let x = 10
      let text = ''
      if (x > 10) {
        text = 'maior que dez =)'
      }

      return text
    }
    // v2.0.0
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
