<template>
  <div class="sobre">
    <h1>Sobre nossa página</h1>
    <p>Tudo sobre a configuração do router com o vue js</p>
  </div>
</template>

<script>
export default {
  name: "AboutPage",
  props: {
    msg: String,
  },
};
</script>

<style scoped>
.sobre {
    background-color: green;
    color: black;
    font-size: 14px;
}
</style>
