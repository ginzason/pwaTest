<template>
  <div class="waiting">
    
  </div>
</template>
<script>
  import data from '../data'
  export default {
    data () {
      return {
        'pictures': data.pictures
      }
    }
  }
</script>
<style scoped>
  .waiting {
    padding: 10px;
    color: #555;
  }
</style>