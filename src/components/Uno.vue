<template>
<div>
    <h1>Juego 1</h1>
    <!--<img src="../assets/uno.jpg" alt="hola">-->

    <img :src="imagen" alt="Imagen juego">

    <h4>{{Nombre}}</h4>
    <h4>{{Valor}}</h4>

</div>

  
</template>

<script>



export default {
  name: 'Uno',
  props:{
      imagen:{
          type: String,
      },
      Nombre:{
          type: String,
      },
      Valor:{
          type: Number,
      }
  }
}
</script>
