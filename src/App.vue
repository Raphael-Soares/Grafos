<template>
  <NavbarComp/>
  <div class="main"></div>
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
body { margin: 0; }

.main {
  height: 100vh;
}

</style>
       