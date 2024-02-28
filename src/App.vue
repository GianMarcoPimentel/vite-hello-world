<script>
// il codice della ogica della mia app

    //importo il titolo da AppTitle.vue
  import AppTitle from "./components/AppTitle.vue";
    //importo il Jumbotron da AppHero.vue
  import AppHero from "./components/AppHero.vue";

  export default {
    components: {
      AppTitle,
      AppHero,
    }
  }
</script>

<template>
   <!-- il layout della mia app -->
  <AppTitle></AppTitle>
  <AppHero></AppHero>
</template>

<style>
</style>
