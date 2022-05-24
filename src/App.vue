<template>
  <div class="bg-page">
    <NavbarComp/>
    <div class="main">
      <div class="text-area">
        <div class="title" >O que é a “Teoria dos Grafos?”</div>
        <div class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>
      </div>
      <img src="./images/grafico_exp.png" alt="">
      <div class="text-area">
        <div class="title" >Como a visualização de grafos do Lexinode funciona?</div>
        <div class="text">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</div>
      </div>
      
    </div>
      



  </div>
    <FooterComp/>
</template>

<script>
import NavbarComp from "./components/NavbarComp.vue"
import FooterComp from "./components/FooterComp.vue"


export default {
    components: {
    FooterComp,
    NavbarComp,
}

}
</script>

<style>
body { 
  margin: 0; 
  font-size: 25px;
  font-family: 'Bebas Neue', 'cursive';
}

.bg-page {
  background-image: url("@/images/bgi.jpeg");
  border: solid;
  background-repeat: no-repeat; 

}


.main {
  margin-top: 100px;
  text-align: center;
  margin-inline: 100px;
  color: white;
}

.title{
  font-size: 3rem;;
}

.text-area {
  margin-block: 100px;
}

</style>
       