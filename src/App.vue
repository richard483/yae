<template>
  <img alt="Yae Miko" src="./assets/103255278_p0.jpg">
  <WelcomePage msg="Welcome, dear Yae worshiper!"/>
</template>

<script>
import WelcomePage from './components/WelcomePage.vue';

export default {
  name: 'App',
  components: {
    WelcomePage
}
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 2rem;
}

img {
  height: 32rem;
}
</style>
