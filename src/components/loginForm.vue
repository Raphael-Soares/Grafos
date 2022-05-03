<template>
  <div class="container">
    <div class="box logo">logo</div>
    <div class="box mensagem">mensagem</div>
    <div class="box form">
      <div class="item-form">
              <label for="">Email</label>
      <input type="text">
      </div>
            <div class="item-form">
              <label for="">Senha</label>
      <input type="text">
      </div>
      <button class="loginBtn">Login</button>

    </div>
  </div>
</template>

<script>
export default {

}
</script>

<style>
.container {
  border: solid 1px; 

  
}
.box {
  border: solid 1px;
  margin: 0.5rem auto;
  width:10rem;
  padding: 1.5rem;
  width: 30vw;
}

.logo {
  background-color: blue;
}

.mensagem {
  background-color: yellow;
}
  
.form {
  display: flex;
  flex-direction: column;

}

</style>