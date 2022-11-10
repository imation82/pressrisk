<template>
  <section>
    <Header />
    <HeroSection />
  </section>
</template>

<script>

export default {
  name: "Homepage",
  components: {
    Header: () => import("@/components/Header.vue"),
    HeroSection: () => import("@/components/HeroSection.vue"),
  },
};
</script>
