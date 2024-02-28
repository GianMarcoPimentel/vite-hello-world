<script>
// il codice della ogica della mia app

    //importo il titolo da AppTitle.vue
  import Title from "./components/AppTitle.vue";
    //importo il Jumbotron da AppHero.vue
  import Jumbotron from "./components/AppHero.vue";

  export default {
    components: {
      Title,
      Jumbotron,
    }
  }
</script>

<template>
   <!-- il layout della mia app -->
  <Title></Title>
  <Jumbotron></Jumbotron>
</template>

<style>
</style>
