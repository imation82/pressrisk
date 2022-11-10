<template>
  <section>
    <Header />
    <HeroSection />
    <Products />
  </section>
</template>

<script>

export default {
  name: "Homepage",
  components: {
    Header: () => import("@/components/Header.vue"),
    HeroSection: () => import("@/components/HeroSection.vue"),
    Products: () => import("@/components/Products.vue"),
  },
};
</script>
