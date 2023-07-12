<script>
// Imposrto i componenti 
import AppTitle from './components/AppTitle.vue'
// my-component.js
export default {
  data() {
    return { count: 10 }
  },
  // Dichiaro i componenti 
  components : {AppTitle}
}
</script>

<template>
  <div>
   {{ count }}
  </div>
</template>

<style scoped>


</style>
