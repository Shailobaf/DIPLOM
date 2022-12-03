<template>
  <HeaderCli />
  <MainCli />
</template>

<script>
import HeaderCli from './components/HeaderCli.vue';
import MainCli from './components/MainCli.vue';
export default {
  name: 'App',
  components: {
    HeaderCli,
    MainCli
  }
}
</script>

<style>
#app {
  background-image: url('assets/home-bg-01.jpg');
  background-position: top 33% center;
  background-size: cover;
  height: 100vh;
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  padding: 0;
  margin: 0;
  margin-top: 60px;
}
</style>
