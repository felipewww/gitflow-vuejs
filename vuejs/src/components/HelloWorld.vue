<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <p>v2.0.1 HOTFIX</p>
    <p>v2.0.1 HOTFIX v2</p>
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
        text = 'Maior que dez! =)'
      } else {
        // else no card #3 que deve ser deletado
        text = 'ou é maior ou menor'
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
