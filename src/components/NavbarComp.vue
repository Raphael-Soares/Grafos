<template>
    <div class="navbar">

        <div class="row lexinode">
            <div class="lexi">LEXI</div><div class="node">NODE</div> 
        </div>

        <div class="row push">
            <a href="#" class="item">ARTIGOS</a>
            <a href="#" class="item push">AUTORES</a>
        </div>

        <div class="row ">
            <a href="#" class="item ">CRIAR CONTA</a>
            <a href="#" class="item ">ENTRAR</a>
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
    text-decoration: none;
    color: white;
    margin-inline: 20px;
    transition: 0.2s;
}

.item:hover {
    color: #0952DB;
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


