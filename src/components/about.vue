<template>
    <div class="about"><br>
      <h1>About Me</h1><br>
      <img id="me" src="https://scontent.fcrk1-4.fna.fbcdn.net/v/t39.30808-6/222779621_6047786251928959_3012027671697752069_n.jpg?_nc_cat=109&ccb=1-7&_nc_sid=09cbfe&_nc_ohc=7MZ3j1cKG_oAX92VKJU&_nc_ht=scontent.fcrk1-4.fna&oh=00_AfBBD2od0Za_UJW9H1P58WLW3-tFRFAkIr7g9QSG76h67Q&oe=64493362"><br>
      <br><h2>Name: Lance Alford Gerard G. Atendido</h2>
      <h2>Contact: 097714186268</h2>
      <h2>Email: alford.atendido@gmail.com</h2>
      <h1>Short Introduction:</h1>
      <h3>iPhones are cool</h3>
    </div>
  </template>
  
  
  <script>
  export default {
    name: 'about',
    data () {
      return {
        title: 'about'
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
  #me{
    width: 850px;
  }
  </style>