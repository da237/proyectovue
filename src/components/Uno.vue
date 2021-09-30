<template>
<div>
    <div class="container">
        <div class="row">
            <div class="card" style="width: 17rem;">
              <img src="@/assets/topoum_01.jpg" alt="hola" class="card-img-top" >
              <div class="card-body">
                <h5 class="card-title">Topoum</h5>
                <p class="card-text">{{card.valor}}</p>
                <a href="#" class="btn btn-primary">Añadir Carrito</a>
              </div>
            </div>
            <div class="card" style="width: 17rem;">
              <img :src="card.url" alt="hola" class="card-img-top" >
              <div class="card-body">
                <h5 class="card-title" >{{card.nombre}}</h5>
                <p class="card-text">{{card.valor}}</p>
                <button class="btn btn-primary">Añadir Carrito</button>
              </div>
            </div>
            <div class="card" style="width: 17rem;">
              <img src="@/assets/root_01.png" alt="hola" class="card-img-top" >
              <div class="card-body">
                <h5 class="card-title">Root</h5>
                <p class="card-text">{{card.valor}}</p>
                <a href="#" class="btn btn-primary">Añadir Carrito</a>
              </div>
            </div>
            <div class="card" style="width: 17rem;">
              <img src="@/assets/peak_oil_01.jpg" alt="hola" class="card-img-top" >
              <div class="card-body">
                <h5 class="card-title">Peak Oil</h5>
                <p class="card-text">{{card.alor}}</p>
                <a href="#" class="btn btn-primary">Añadir Carrito</a>
              </div>
            </div>
        </div>
    </div>

</div>
</template>

<script>

export default {
  name: 'Uno',
  data(){
     
  },
  props:{
      Id:{
        type: Number,
      },
      Url:{
          type: String,
      },
      Nombre:{
          type: String,
      },
      Valor:{
          type: Number,
      },
      card:{
      type:Object,
      default: () => {},
    },
  }
}
</script>
