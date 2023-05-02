<script>

  import PrimoComponente from './components/PrimoComponente.vue';

  export default{
    name: "App",
    components: {
      PrimoComponente
    }
  }
  

</script>

<template>
  <h1>La Mia Prima App Con Vite!</h1>
  <PrimoComponente/>
</template>

<style scoped>

  template{
    background-color: rgb(27, 27, 27);
  }

  h1{
    color: gold;
  }

</style>
