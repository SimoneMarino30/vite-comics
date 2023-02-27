<script>
export default {
  data() {
    return { title: "MiddleBar" };
  },
};
</script>

<template>
  <section>
    <img src="../assets/img/buy-comics-digital-comics.png" alt="" />
    <span>DIGITAL COMICS</span>

    <img src="../assets/img/buy-comics-merchandise.png" alt="" />
    <span>DC MERCHANDISE</span>

    <img src="../assets/img//buy-comics-subscriptions.png" alt="" />
    <span>SUBSCRIPTION</span>

    <img src="../assets/img/buy-comics-shop-locator.png" alt="" />
    <span>COMIC SHOP LOCATOR</span>

    <img src="../assets/img/buy-dc-power-visa.svg" alt="" />
    <span>DC POWER VISA</span>
  </section>
</template>

<style lang="scss" scoped>
section {
  display: flex;
  justify-content: center;
  align-items: center;
  min-height: 10rem;
  margin: 0 auto;
  background-color: #0282f9;
  color: white;

  img {
    max-width: 60px;
    max-height: 60px;
  }

  span {
    min-width: 100px;
    padding: 0 1rem;
  }
}
</style>
