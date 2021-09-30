<template>
<div>
    <p></p>
    <h5>RECIÉN LLEGADOS</h5>
    <div class="col-12 d-flex px-5 flex-row justify-content-around my-3 flex-wrap">
      <div class="d-flex flex-fill flex-column caja p-4 mx-2 my-lg-1 text-center">
        <uno  v-for="(d, $index) in info" :key="$index" :card="d" ></uno>
      </div>
      <!-- <div>
        <uno v-for="(d, $index) in info" :key="$index" :card="d"></uno>
      </div>

      <div>
        <uno v-for="(d, $index) in info" :key="$index" :card="d"></uno>
      </div> -->
    </div>
    <!-- <uno :Nombre="'Fifa 2021'" :Valor="15000" ></uno> -->
    <p></p>
    <h5>PROXIMAMENTE</h5>
    <div>
      <div>
        <dos :Nombre="'Dixit'" :Valor="12000" ></dos>
      </div>
    </div>

    
</div>
</template>

<script>
import Uno from '../components/Uno.vue'
import Dos from '../components/Dos.vue' 


export default {
  name: 'Principal',
  components: {
    Uno, Dos
  },
   data() {
    return {
      info: [
        { 
          id: 1,
          url: "https://http2.mlstatic.com/D_NQ_NP_822302-MCO40352886432_012020-O.webp",
          nombre: "Halo",
          valor: 1500,
        },
        {
          id: 2,
          url: "https://http2.mlstatic.com/D_NQ_NP_816910-MCO47245042056_082021-O.webp",
          nombre: "Fifa",
          valor: 2000,
        },
        {
          id:  3,
          url: "https://http2.mlstatic.com/D_NQ_NP_875637-MCO31035401457_062019-O.webp",
          nombre: "Mario Kart",
          valor: 2500,
        },
        /* {
          id: 4,
          url: "https://www.unplugandplay.co/2609-medium_default/topoum.jpg",
          nombre: "Topoum",
          valor: 3000,
        },
        {
          id: 5,
          url: "https://www.unplugandplay.co/1644-medium_default/dixit-classic.jpg",
          nombre: "Dixit",
          valor: 3500,
        }, */
      ],
      
    };
  },
 
}

</script>
