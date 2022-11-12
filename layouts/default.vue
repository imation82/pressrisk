<template>
    <section>
        <Header />
        <div>
            <Nuxt />
        </div>
        <Footer />
    </section>
</template>
  
<script>
export default {
    name: "DefaultLayout",
    components: {
        Header: () => import("@/components/Header.vue"),
        Footer: () => import("@/components/Footer.vue"),
    },
};
</script>
  