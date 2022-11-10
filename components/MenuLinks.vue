<template>
  <ul class="menuLinks">
    <li><a href="#about" class="desktopView-items">About</a></li>
    <li><a href="#products" class="desktopView-items">Products</a></li>
    <li><a href="#team" class="desktopView-items">Team</a></li>
    <li><a href="#contact" class="desktopView-items">Contact</a></li>
  </ul>
</template>

<script>
export default {
  props: {
    sticky: {
      type: Boolean,
      default: false,
    },
  },
};
</script>
<style scoped>
@import "@/assets/styles/menuLinks.css";
</style>
