<script>
export default {
  props: {
    card: Object,
  },
};
</script>

<template>
  <li>
    <img :src="card.thumb" alt="" />
    <h3>{{ card.series }}</h3>
  </li>
</template>

<style lang="scss" scoped>
li {
  display: flex;
  flex-direction: column;
  flex-wrap: wrap;
  margin: 10px;
  //   border: 3px dashed blue;
  img {
    width: 170px;
    height: 200px;
  }

  h3 {
    // border: 3px dashed orange;
    width: 170px;
    text-transform: uppercase;
  }
}
</style>
