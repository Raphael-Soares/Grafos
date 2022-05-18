<template>
    <div class="navbar">
        <div class="row start">
            <div class="brand row">
                <div class="lexi">LEXI</div><div class="node">NODE</div> 
            </div>
            
            <div class="item">ARTIGOS</div>
            <div class="item">AUTORES</div>
        </div>
        <div class="row">
            <div class="item ">CRIAR CONTA</div>
            <div class="item ">ENTRAR</div>
        </div>
    </div>
</template>

<script>
export default {
  data(){
    return {

    }
  }

}
</script>

<style >
@import url('https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap');
:root{
    font-family: Arial, Helvetica, sans-serif;
}


.navbar {
    font-size: 1.5rem;
    font-family: 'Bebas Neue', 'cursive';
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding: 10px;
    /* background-color: black; */
}
.navbar .row{
    display: flex;
    flex-direction: row;
    align-items: center;
    color: aliceblue;
}


.brand {
    font-size: 2.5rem;
    font-family: 'Bebas Neue';
}

.brand .node {
    color:#0952DB;
}

.item {

    margin-left: 50px;
}


</style>


