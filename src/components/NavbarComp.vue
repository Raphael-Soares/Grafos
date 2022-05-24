<template>
    <div class="navbar">

        <div class="row lexinode">
            <div class="lexi">LEXI</div><div class="node">NODE</div> 
        </div>

        <div class="row push">
            <div class="item">ARTIGOS</div>
            <div class="item push">AUTORES</div>
        </div>

        <div class="row ">
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


.navbar {
    font-size: 2rem;
    font-family: 'Bebas Neue', 'cursive';
    color: white;

    padding: 15px;
    
    display: flex;
    flex-direction: row;
    justify-content: space-around;

}
.row{
    display: flex;
    align-items: center;
}
.item {
    
    margin-inline: 20px;
}

.push {
    margin-right: auto;
}

.lexinode {
    display: flex;
    font-size: 3rem;
    margin-right: 20px;
}

.lexinode .node {
    color:#0952DB;
}




</style>


