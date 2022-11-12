<template>
  <section>
    <Header />
    <HeroSection />
    <About />
    <Products />
    <Team />
    <Contact />
    <Footer />
  </section>
</template>

<script>

export default {
  name: "Homepage",
  components: {
    Header: () => import("@/components/Header.vue"),
    HeroSection: () => import("@/components/HeroSection.vue"),
    About: () => import("@/components/About.vue"),
    Products: () => import("@/components/Products.vue"),
    Team: () => import("@/components/Team.vue"),
    Contact: () => import("@/components/Contact.vue"),
    Footer: () => import("@/components/Footer.vue"),
  },
};
</script>
