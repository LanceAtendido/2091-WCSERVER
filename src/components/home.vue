<template>
    <div class="home">
      <h1>Welcome to the Home Page of iPHONE</h1>
      <h3>THE iPHONE</h3>
      <img id = "iphone" src ="https://i.redd.it/t49ftjob0rb91.jpg">
    </div>
  </template>
  
  
  <script>
  export default {
    name: 'home',
    data () {
      return {
        title: 'Home'
      }
    }
  }
  </script>
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped>
  h1{
    color: black;
    text-align: center;
  }
  #fruit{
    width: auto;
  }
  </style>