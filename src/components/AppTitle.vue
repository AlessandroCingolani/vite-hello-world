  <script>
  export default {
    name: 'AppTitle',
    data(){
      return {
        title: 'La mia prima app con Vite!'

      }
    }
  }
  </script>
  
<template>
  <h1>{{ title }}</h1>
</template>


<style scoped>
  h1 {
    margin-top: 50px;
    text-align: center;
    color: green;
  }
</style>