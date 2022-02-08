<script>
import { defineComponent } from 'vue'
import Kilometrage from './components/Kilometrage.vue'
export default defineComponent({
  name: 'App',
  components: {
    Kilometrage
  }
});
</script>

<template>
  <Kilometrage />
</template>