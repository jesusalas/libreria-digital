<template>
   <div class="container">
      <div class="register-container col-md-10 offset-md-2">
         <h1>Crea tu cuenta</h1>
         <form action="">
            <div class="form-group row">
               <label for="" class="col-sm-2 col-form-label">Nombre:</label>
                <div class="col-sm-10">
                  <input type="text" class="form-control" name="" id="">
                </div>
            </div>
            <div class="form-group row">
               <label for="" class="col-sm-2 col-form-label">Correo:</label>
                <div class="col-sm-10">
                  <input type="text" class="form-control" name="" id="">
                </div>
            </div>
            <div class="form-group row">
               <label for="" class="col-sm-2 col-form-label">Usuario:</label>
                <div class="col-sm-10 text-left">
                  <input type="text" class="form-control" name="" id="">
                  <small id="userInputText" class="form-text text-danger">El usuario ya existe</small>
                </div>
            </div>
            <div class="form-group row">
               <label for="" class="col-sm-2 col-form-label">Contraseña:</label>
                <div class="col-sm-10">
                  <input type="text" class="form-control" name="" id="">
                </div>
            </div>
            <div class="form-group row">
               <label for="" class="col-sm-2 col-form-label">Confirmar Contraseña:</label>
                <div class="col-sm-10 text-left">
                  <input type="text" class="form-control" name="" id="">
                  <small id="userInputText" class="form-text text-danger">Las contraseñas no coinciden</small>
                </div>
            </div>
            <div class="form-group row">
               <div class="col-sm-12">
                  <button class="btn btn-primary">Registrar</button>
               </div>
            </div>
         </form>
      </div>
   </div>
</template>
<script></script>
<style>
    body{
      background-color: #E6E6E6;
   }
   .register-container{
      padding-bottom: 20px;
      background-color: white;
      border-radius: 2px;
   }
</style>
