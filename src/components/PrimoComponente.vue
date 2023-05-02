<script>

  export default{
    name: "PrimoComponente",
    data(){
      return{
       
      }
    },
    methods: {

    },
    name: "ContatoreComp",
    data() {
        return {
            contatore: 20
        }
    }
  }
  
</script>

<template>
    <div>
        <h1>La Mia Prima App Con Vite!</h1>
    </div>

    <div>
        <button @click="contatore--">Premi e ripremi per continuare il conto alla rovescia manuale</button>
    </div>

    <div id="mina">
        <img src="../assets/mina-sfondo-nero.jpg" alt="mina">
    </div>

    <div>
        <span id="countdown">{{ contatore }}</span>
    </div>

</template>

<style scoped>

    template{
        background-color: rgb(26, 26, 26);
    }

    h1{
        color: gold;
    }

    #countdown {
        color: yellowgreen;
        font-size: larger;
    }

  
</style>