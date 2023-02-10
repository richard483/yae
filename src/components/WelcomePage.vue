<template>
      <h1>{{ msg }}</h1>
      <p>
        Yang punya web masih sibuk ngebuild Yae, jadi belum sempat bikin webnya. Tapi kalo mau liat-liat yg lain, bisa ke <a href="https://www.nephren.xyz">website utama</a> nya.
      </p>
  </template>
  
  <script>
  export default {
    name: 'WelcomePage',
    props: {
      msg: String
    }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  a {
    color: #FFB7C6;
  }
  </style>
  