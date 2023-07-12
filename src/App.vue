<script>
// Importo i componenti 
import AppTitle from './components/AppTitle.vue'
import AppHero from './components/AppHero.vue'

// my-component.js
export default {
  data() {
    return {  }
  },
  // Dichiaro i componenti 
  components : {AppTitle,
          AppHero}
}
</script>

<template>
  <!-- Utilizzo dei componenti -->
  <AppTitle/>
  <AppHero/>
  <div>
   {{ count }}
  </div>
</template>

<style scoped>


</style>
