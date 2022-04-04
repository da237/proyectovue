<template>
<div>
    <div class="container">
        <div class="row">
            <div class="card" style="width: 17rem;">
              <img src="@/assets/dixit-clasic.png" alt="hola" class="card-img-top" >
              <div class="card-body">
                <h5 class="card-title">{{Nombre}}</h5>
                <p class="card-text">{{Valor}}</p>
                <a href="#" class="btn btn-primary">Añadir Carrito</a>
              </div>
            </div>
            <div class="card" style="width: 17rem;">
              <img src="@/assets/dixit-odyssey.png" alt="hola" class="card-img-top" >
              <div class="card-body">
                <h5 class="card-title">{{Nombre}}</h5>
                <p class="card-text">{{Valor}}</p>
                <a href="#" class="btn btn-primary">Añadir Carrito</a>
              </div>
            </div>
            <div class="card" style="width: 17rem;">
              <img src="@/assets/dixit-2-quest.png" alt="hola" class="card-img-top" >
              <div class="card-body">
                <h5 class="card-title">{{Nombre}}</h5>
                <p class="card-text">{{Valor}}</p>
                <a href="#" class="btn btn-primary">Añadir Carrito</a>
              </div>
            </div>
            <div class="card" style="width: 17rem;">
              <img src="@/assets/dixit-3-journey.png" alt="hola" class="card-img-top" >
              <div class="card-body">
                <h5 class="card-title">{{Nombre}}</h5>
                <p class="card-text">{{Valor}}</p>
                <a href="#" class="btn btn-primary">Añadir Carrito</a>
              </div>
              
            </div>
        </div>
    </div>

</div>
</template>

<script>

export default {
  name: 'Dos',
  data(){
     /* Articulos:[{ 
          imagen: "@/assets/mario.png",
          Nombre:'MARIO',
          Valor: 15000
      }]*/
      
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
      
  }
}
</script>
