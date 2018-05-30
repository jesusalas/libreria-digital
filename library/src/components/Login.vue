<template>
  <div class="container">
    <div class="login-container col-md-6 offset-md-3">
      <form>
        <div class="col-sm-12">
          <img src="../assets/logo.png" clas="img-fluid">
        </div>
        <div class="form-group text-left">
          <input type="text" name="userInputText" id="userInputText" placeholder="usuario" class="form-control">
          <small id="userInputText" class="form-text text-danger">Usuario no encontrado</small>
        </div>
        <div class="form-group text-left">
          <input type="text" name="passwordInputText" id="passwordInputText" placeholder="contraseña" class="form-control">
          <small id="passwordInputText" class="form-text text-danger">Contraseña incorrecta</small>
        </div>
        <div class="row">
          <div class="col-md-6">
            <button class="btn btn-primary">Iniciar</button>
          </div>
          <div class="col-md-6">
            <a href="">crear cuenta</a>
          </div>
        </div>
      </form>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Login',
  data () {
    return {
      msg: 'Bienvenidos a la Libreria Digital mas amplia del mundo'
    }
  }
}
</script>

<style>
  body{
    background-color: #E6E6E6;
  }
  img{
    height: 50%;
    width: 50%;
  }
  .login-container{
    padding-bottom: 20px;
    background-color: white;
    border-radius: 2px;
  }
</style>
