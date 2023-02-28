<script>
export default {};
</script>

<template>
  <main>
    <div class="main-img"></div>
    <label for="">CURRENT SERIES</label>
    <div class="main-content">dddd</div>
  </main>
</template>

<style lang="scss" scoped>
@use "../src/assets/scss/general.scss";

main {
  background-image: url(../assets/img/jumbotron.jpg);
  position: relative;
  display: flex;
  flex-direction: column;
  justify-content: end;
  min-height: 90vh;
  .main-img {
  }

  label {
    position: absolute;
    top: 500px;
    left: 250px;
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
    background-color: #1c1c1c;
    color: white;
    // debug
    height: 20rem;
  }
}
</style>
