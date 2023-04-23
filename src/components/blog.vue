<template>
    <div class="blog"><br>
      <h1>The iPhone over the years</h1><br>
      <img id = "fruit" src ="https://imgnew.outlookindia.com/public/uploads/articles/2021/9/15/Apple_iPhones_over_the_years1.JPG">
      <h2></h2><br>
      <h3>Jobs saw in 2002, following the release of the iPod, that the overlapping markets for mobile phones and music players would compel Apple to enter the mobile phone industry. He believed that someday consumers will choose just one gadget after observing millions of Americans using separate BlackBerrys, phones, and Apple's iPod MP3 players.</h3>
    </div>
  </template>
  
  
  <script>
  export default {
    name: 'blog',
    data () {
      return {
        title: 'Blog'
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
  h3{
    text-align: justify;
  }
  </style>