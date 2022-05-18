<template>
  <div class="page">
    <NavbarComp/>
    <div class="main">
      <div class="main-title">
        O que é a “Teoria dos Grafos?”
      </div>
      <div class="main-text">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
      </div>
    </div>
      <div class="image"></div>



    <FooterComp/>
  </div>
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
      font-size: 1.5rem;
    font-family: 'Bebas Neue', 'cursive';
;}


.page {
  background-image: url("@/images/bgi.jpg");
  background-repeat: no-repeat
}

.main {
  margin-top: 100px;
  height: 120vh;
  text-align: center;
  color: aliceblue;

}

.main-title{
  font-size: 2.5rem;;

}
.main-text {
  padding: 100px;
  font-size: 1.5rem;
  
}

.image {
  background-image: url("@/images/graf.jpg");
  background-repeat: no-repeat;
  height: 100%;
  width: 100%;
  object-fit: cover;
  margin: 0;
  position: absolute;
  top: 1000px;

}


</style>
       