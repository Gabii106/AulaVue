<template>
  <h1> Seja bem-vindo</h1>
  <p>{{msg}}</p>
</template>

<script>

export default {
  name: 'HomePage',
  props: {
    msg: String
  }
}
</script>

<style scoped>
  p {
    color: red;
  }
</style>
