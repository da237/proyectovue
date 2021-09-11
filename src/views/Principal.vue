<template>
<div>
    <p></p>
    <h5>RECIÉN LLEGADOS</h5>
    <uno :Nombre="'Fifa 2021'" :Valor="15000" ></uno>
    <Dos :Nombre="'Mario'" :Valor="18000" ></Dos>
    <p></p>
    <h5>PROXIMAMENTE</h5>
    <Tres :Nombre="'Dixit'" :Valor="12000" ></Tres>

    
    

</div>
</template>

<script>
import Uno from '../components/Uno.vue'
import Dos from '../components/Dos.vue'
import Tres from '../components/Tres.vue'

export default {
  name: 'Principal',
  components: {
    Uno, Dos,Tres
  }, 
}

</script>
