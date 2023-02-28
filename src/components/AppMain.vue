<script>
import MoviesList from "../components/MoviesList.vue";

export default {
  // props: {
  //   card: Array,
  // },
  components: { MoviesList },
};
</script>

<template>
  <section>
    <label for="">CURRENT SERIES</label>
    <div class="main-content">
      <MoviesList />
      <!-- <MovieCard v-for="movie in MoviesList" :card="movie" /> -->
    </div>
  </section>
</template>

<style lang="scss" scoped>
@use "../src/assets/scss/general.scss";

section {
  background-image: url(../assets/img/jumbotron.jpg);
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: end;
  min-height: 90vh;

  label {
    position: absolute;
    top: 28.5rem;
    left: 20rem;
    border: 1px solid black;
    background-color: #0282f9;
    color: white;
    width: 200px;
    height: 50px;
    display: flex;
    justify-content: center;
    align-items: center;
  }

  .main-content {
    margin-top: 30rem;
    background-color: #1c1c1c;
    color: white;
    // debug
    border: 3px dashed yellowgreen;
  }
}
</style>
