<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import MiddleBar from "./components/MiddleBar.vue";
import AppFooter from "./components/AppFooter.vue";
// import MoviesList from "./components/MoviesList.vue";
// import MovieCard from "./components/MovieCard.vue";

export default {
  data() {
    return {};
  },

  components: { AppHeader, AppMain, MiddleBar, AppFooter },
  // , MoviesList
};
</script>

<template>
  <header>
    <AppHeader />
  </header>
  <main>
    <AppMain />
    <!-- <MoviesList /> -->
    <MiddleBar />
  </main>
  <footer>
    <AppFooter />
  </footer>
</template>

<style lang="scss">
@use "../src/assets/scss/general.scss";
</style>
