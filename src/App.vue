<template>
  <the-interface />
</template>

<script>
import TheInterface from "./components/TheInterface";

export default {
  name: "new-name",
  components: {
    TheInterface
  },
  mounted() {
    this.$store.commit("initialize");
  }
};
</script>

<style></style>
