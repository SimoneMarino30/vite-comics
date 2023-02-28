<script>
export default {
  data() {
    return { title: "AppHeader" };
  },
};
</script>

<template>
  <header>
    <img src="../assets/img/dc-logo.png" alt="" />
    <ul>
      <li><a href="">CHARACTERS</a></li>
      <li><a href="">COMICS</a></li>
      <li><a href="">MOVIES</a></li>
      <li><a href="">TV</a></li>
      <li><a href="">GAMES</a></li>
      <li><a href="">COLLECTIBLES</a></li>
      <li><a href="">VIDEOS</a></li>
      <li><a href="">FANS</a></li>
      <li><a href="">NEWS</a></li>
      <li><a href="">SHOP</a></li>
    </ul>
  </header>
</template>

<style lang="scss" scoped>
// @use "../assets/scss/partials/mixin.scss as*";
@use "../assets/scss/general.scss";

header {
  max-width: 1200px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  min-height: 5rem;
}

img {
  padding: 20px;
}
li {
  display: inline-block;
  padding: 0.5rem;
  a {
    text-decoration: none;
  }
}
</style>
