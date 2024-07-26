<script>
  import AppTitle from './components/AppTitle.vue';
  import AppJumbo from './components/AppJumbo.vue';
  export default {
    components: {
      AppTitle,
      AppJumbo
    }
  }
</script>

<template>
 <header>
    <AppTitle />
 </header>
 <main>
    <AppJumbo />
 </main>
</template>

<style scoped>
  
</style>
