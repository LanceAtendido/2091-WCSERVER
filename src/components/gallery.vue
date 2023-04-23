<template>
    <div class="gallery"> 
      <h1>iPhone Gallery</h1>
      <img id = "fruit" src ="https://www.macworld.com/wp-content/uploads/2023/01/original-iphone-2007.jpg?quality=50&strip=all&w=1024"><br>
      <img id = "fruit" src ="https://store.storeimages.cdn-apple.com/8756/as-images.apple.com/is/iphone-12-finish-unselect-gallery-1-202207_FMT_WHH?wid=1280&hei=492&fmt=p-jpg&qlt=80&.v=1662129044220"><br>
      <img id = "fruit" src ="https://www.apple.com/ph/iphone/home/images/meta/iphone__ky2k6x5u6vue_og.png"><br>   
      <img id = "fruit" src ="https://www.apple.com/newsroom/images/product/iphone/standard/Apple-iPhone-14-iPhone-14-Plus-hero-220907_Full-Bleed-Image.jpg.large.jpg"><br> 
    </div>
  </template>
  
  
  <script> 
  export default {
    name: 'gallery', 
    data () {
      return {
        title: 'Gallery'
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
    width: 1000px;
  }
  </style>