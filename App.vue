<template>
  <div class="container">
   <div>
     <cv-satu />
   </div>
   <hr>
   <div class="container"></div>
     <cv-dua/>
     <br>
     <br>
     </div>
     
</template>
<script>
import CvSatu from './components/CvSatu.vue'
import CvDua from './components/CvDua.vue'

export default {
  name: 'App',
  components: {
    CvSatu,
    CvDua
  }
}
</script>

<style>
#app {
    background-color:white;
    margin: 50px;
}
</style>
