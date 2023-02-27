<script>
export default {
  data() {
    return { title: "--> Content Goes here <--" };
  },
};
</script>

<template>
  <main>{{ title }}</main>
</template>

<style lang="scss" scoped>
@use "../src/assets/scss/general.scss";

main {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 10rem;
  margin: 0 auto;
  background-color: #1c1c1c;
  color: white;
}
</style>
