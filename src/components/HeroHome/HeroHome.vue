<script setup>
import HeroText from './HeroText.vue';
import FotoHero from './FotoHero.vue';
</script>
<template>
    <main>
        <HeroText />
        <FotoHero />
    </main>
</template>
<style scoped>
main{
    width: 100%;
    height: 80vh;
    padding: 0 10%;
    display: grid;
    grid-template-columns: 1fr 1fr;
    align-items: center;
    gap: 1rem;
}
</style>
