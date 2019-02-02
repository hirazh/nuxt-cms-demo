<template>
    <div class="blogContainer">
        <Navbar/>
        <h1>All Blogs</h1>
        <div>
            <p>
                The space wil be filled with wonderful blog posts
            </p>
        </div>
    </div>
</template>

<script>
import Navbar from '@/components/Navbar.vue'

export default {
  
  components: {
    Navbar
  }
}
</script>

<style scoped>
.blogContainer {
    text-align: center;
}
</style>
