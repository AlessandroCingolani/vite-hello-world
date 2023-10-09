<script>
export default {
  name: 'AppHero',
  data(){
    return {
      titleJumbo: 'Jumbotron'
    }
  }
}
</script>

<template>
  <div id="jumbotron">
    <h2>{{ titleJumbo }}</h2>
    <img src="../../public/vite.svg" alt="vite">
  </div>
</template>


<style scoped>
  #jumbotron {
    margin-top: 50px;
    text-align: center;
    color: rgb(52, 71, 95);
  }

  h2 {
    font-size: 1.7rem;
  }

  img {
    margin-top: 20px;
    width: 100px;
  }



</style>