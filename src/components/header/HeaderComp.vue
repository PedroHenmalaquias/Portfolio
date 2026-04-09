<script setup>
import HeaderLogo from './HeaderLogo.vue'
import HeaderNav from './HeaderNav.vue'
import HeaderLinks from './HeaderLinks.vue';
</script>

<template>
    <header>
        <HeaderLogo />
        <HeaderNav />
        <HeaderLinks />
    </header>
</template>
<style scoped>
header{
    /* gap: 2rem; */
    min-height: 100px;
    max-height: 20vh;
    width: 100%;
    padding: 0 10%;
    /* padding-right: 10%; */
    /* padding-left: 10%; */
    /* margin: 0 auto; */
    display: grid;
    grid-template-columns: 1fr 4fr 1fr;
    align-items: center;
    background-color: transparent;
}
</style>