<template>
  <div>
    <div col>
 
      <iframe src="https://www.google.com/maps/embed?pb=!1m14!1m12!1m3!1d15863.705921135264!2d-75.59026551511229!3d6.273397812034287!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!5e0!3m2!1ses!2sco!4v1631252439158!5m2!1ses!2sco" width="800" height="600" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      <b-form @submit="onSubmit" @reset="onReset" v-if="show">
      <b-form-group
        label="Direccion de Correo:"
       
      >
        <b-form-input
          
          v-model="form.email"
          type="email"
          placeholder="Ingrese email"
          required
        ></b-form-input>
      </b-form-group>
 
      <b-form-group id="input-group-2" label="Nombre:" label-for="input-2">
        <b-form-input
          id="input-2"
          v-model="form.name"
          placeholder="Ingrese Nombre"
          required
        ></b-form-input>
      </b-form-group>
 
      <b-form-group id="input-group-3" label="Interes:" label-for="input-3">
        <b-form-select
          id="input-3"
          v-model="form.food"
          :options="foods"
          required
        ></b-form-select>
      </b-form-group>
      <b-button type="submit" variant="primary">Enviar</b-button>
      <!--<b-button type="reset" variant="danger">Reset</b-button>-->
    </b-form>
    <!--<b-card class="mt-3" header="Form Data Result">
      <pre class="m-0">{{ form }}</pre>
    </b-card>-->
     <div>
        <h4>Encuentranos</h4>
 
        <p>
          Proyecto Vue IUSH <br>
          Carrera 1a # 02-03,Medellin,Antioquia <br>
          Telefono +57 300000000 <br>
          Email admin@comunidadiush.edu.co
        </p>
      </div>
 
    </div>
  </div>
</template>
 
<script>
  export default {
    name:'About',
    data() {
      return {
        form: {
          email: '',
          name: '',
          food: null,
          checked: []
        },
        foods: [{ text: 'Seleccione una', value: null }, 'Proveedor', 'Busca empeleo', 'Quejas', 'Corn'],
        show: true
      }
    },
    methods: {
      onSubmit(event) {
        event.preventDefault()
        alert(JSON.stringify(this.form))
      },
      onReset(event) {
        event.preventDefault()
        // Reset our form values
        this.form.email = ''
        this.form.name = ''
        this.form.food = null
        this.form.checked = []
        // Trick to reset/clear native browser form validation state
        this.show = false
        this.$nextTick(() => {
          this.show = true
        })
      }
    }
  }
</script>
