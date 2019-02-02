<template>
<div class="containernavbar">
    <div class="navItem">
        <nuxt-link to="/">Home</nuxt-link>
    </div>
    <div class="navItem">
        <nuxt-link to="/blogs">All Blogs</nuxt-link>
    </div>
</div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
.containernavbar {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 2%;
}

.navItem {
    font-size: 1.5rem;
    margin-left: 5%;
    margin-right: 5%;
}
</style>
