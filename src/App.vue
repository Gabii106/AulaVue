<template>
  <nav>
    <router-link to="/"> Início </router-link>
    <router-link to="/sobre"> Sobre </router-link>
  </nav>

  <router-view></router-view>
</template>

<script>


export default {
  name: "App"
};

</script>

<style>
  nav {
    padding: 3px;
  }

  a{
    padding: 3px;
    background-color: red;
  }

  a:hover{
    background-color: gray;
  }
</style>
