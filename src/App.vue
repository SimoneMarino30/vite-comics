<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import MiddleBar from "./components/MiddleBar.vue";
import AppFooter from "./components/AppFooter.vue";

export default {
  data() {
    return {
      title: "App",
    };
  },

  components: { AppHeader, AppMain, MiddleBar, AppFooter },
};
</script>

<template>
  <AppHeader />
  <AppMain />
  <MiddleBar />
  <AppFooter />
</template>

<style scoped></style>
