<template>
  <div>
    <input type="text" v-model="nom" /> Nom
    <br>
    <input type="text" v-model="prenom" /> Prenom
    <br>
    <input type="text" v-model="date" /> Date de naissance
    <br>
    <input type="text" v-model="email" /> Lieu
    <br>
    <button type="button" v-on:click="goto()">Valider</button>
  </div>
</template>

<script>
import { defineComponent } from 'vue';

export default defineComponent({
  data:() => {
    return {
    nom: "",
    prenom: "",
    date: "",
    email: "",
    }
  },
 methods : {
    goto(){
      window.location.href = 'accueil'
    }
  }
});
</script>