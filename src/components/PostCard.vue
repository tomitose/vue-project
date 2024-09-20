<script setup lang="ts">
import PostButton from './PostButton.vue';


</script>

<template>
    <div class="post-card ">
        <h3>Título</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Illo expedita exercitationem doloremque nulla eius cumque minus officiis consequuntur nemo, culpa mollitia rerum assumenda corporis aut rem sed quam? Iusto, dolores?</p>
        <PostButton/>
    </div>
</template>

<style scoped>
    .post-card{
        border-radius: 12px;
        padding: 10px;
        margin: 6px;
        border: 1px solid #ccc;
    }
</style>