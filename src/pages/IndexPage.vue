<template>
  <q-page>
    <div class="q-pa-md">
    <div style="max-width : 300px">
    <q-form @submit="SubmitForm"
    <div>
      <q-input label = "UserName" v-model="textInput" />
    </div>
    <div>
      <q-btn type="Submit" label = "Submit" />
    </div>
    </q-form>
    </div>
  </q-page>
</template>


<script>
import { defineComponent } from 'vue';

export  default defineComponent( options:{
name" 'PageIndex',
  data() {
    return{
        formData : {
            textInput : null
        }
    }
  }


methods:{
  submitForm(){
      alert( 'Your Name is :' + this.formData.textinput)
  }
}
})
</script>
