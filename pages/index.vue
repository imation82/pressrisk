<template>
  <section>
    <HeroSection />
    <About />
    <Products />
    <Contact />
  </section>
</template>

<script>

export default {
  name: "Homepage",
  components: {
    HeroSection: () => import("@/components/HeroSection.vue"),
    About: () => import("@/components/About.vue"),
    Products: () => import("@/components/Products.vue"),
    Contact: () => import("@/components/Contact.vue"),
  },
};
</script>
