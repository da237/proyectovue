<template>
<div>
    <h1>Tienda online</h1>

    <img src="../assets/Principal.jpg" alt="hola">

    <uno :Nombre="'Fifa 2021'" :Valor="15000" :imagen=" 'https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQ6Iyc5PA9NTv8p6U0n3IryzWwS2ueQXzyFMQ&usqp=CAU '"></uno>


</div>

  
</template>

<script>
import Uno from '../components/Uno.vue'



export default {
  name: 'Principal',
  components: {
    Uno
  }
}

</script>
