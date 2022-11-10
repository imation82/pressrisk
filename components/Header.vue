<template>
    <section id="home">
        <Navbar />
    </section>
</template>
<script>
export default {
    components: {
        Navbar: () => import("@/components/Navbar.vue"),
    },
};
</script>

