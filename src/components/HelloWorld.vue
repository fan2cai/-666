<template>
  <div class="hello">
    <div class="helloWorld">hello world</div>
  </div>
</template>

<script>
  export default {
    name: 'HelloWorld',
    data () {
      return {
        msg: 'Welcome to Your Vue.js App'
      }
    }
  }
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .helloWorld {
    width: 200px;
    height: 200px;
    background: pink;
    margin: 0 auto;
  }
</style>
