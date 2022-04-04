<template>
  <div class="input-group mb-3 container mt-3">
    <div class="input-group-text">
      <form>
        <div class="mb-3">
          <label for="exampleInputEmail1" class="form-label"
            >Correo electronico</label
          >
          <input
            type="email"
            class="form-control"
            id="exampleInputEmail1"
            aria-describedby="emailHelp"
          />
          <div id="emailHelp" class="form-text"></div>
        </div>
        <div class="mb-3">
          <label for="exampleInputPassword1" class="form-label"
            >Contraseña</label
          >
          <input
            type="password"
            class="form-control"
            id="exampleInputPassword1"
          />
          <p class="p1">¿Olvidaste tu contraseña? <br /></p>
          <p>.</p>
        </div>
        <div class="container">
          <button class="btn btn-dark" type="button">Button</button>
        </div>
        <div>
          <h2>Nuevo Cliente</h2>
          <p>
            Es rapido y facil crear una cuenta para comprar mas rapido y guardar
            tu pedido en la <br />
            cuenta
          </p>
          <button type="button" class="btn btn-outline-dark">
            Crear una cuenta
          </button>
        </div>
      </form>
    </div>
  </div>
</template>
 
<script>
export default {
  name: "Usuario",
  components: {},
};
</script>
 
<style lang="scss">
.container {
  justify-content: center;
}
.btn1 {
  justify-content: center;
}

.p1 {
  float: left;
}
</style>