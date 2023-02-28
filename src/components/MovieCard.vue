<script>
export default {
  props: {
    card: Object,
  },
};
</script>

<template>
  <li>
    <img :src="movie.thumb" alt="" />
    <div class="card-title"></div>
  </li>
</template>

<style lang="scss" scoped></style>
