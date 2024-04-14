<template>
  <main>
    <AppHero></AppHero>
    <AppTitle></AppTitle>
  </main>
</template>

<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';

export default {
  components: {
    AppTitle,
    AppHero,
  }
}
</script>

<style lang="scss" scoped>

</style>