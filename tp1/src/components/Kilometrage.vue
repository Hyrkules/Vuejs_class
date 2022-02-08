<template>
  <div>
    <input type="text" v-model="nom" /> Nom
    <br>
    <input type="text" v-model="prenom" /> Prenom
    <br>
    <input type="text" v-model="date" /> Date de naissance
    <br>
    <input type="text" v-model="place" /> Lieu
    <button @click="showpage">Incrémenter</button>
  </div>
</template>

<script>
import { defineComponent } from 'vue';
import { Value } from './Values.vue';

export default defineComponent({
  data: () => {
    return {
      Values
    }
  }
});
</script>