<template>
<div class="post-card">
    <h3>Titulo</h3>
    <p> Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis dignissimos labore ducimus asperiores repudiandae maxime sed corrupti, iure doloremque? Maxime doloremque molestiae laudantium rem a qui aut quasi itaque voluptate?</p>
    <PostButton></PostButton>
</div>
</template>
<script lang="ts" setup>
    import PostButton from './PostButton.vue';
</script>
<style scoped>
    .post-card { 
        border-radius: 15px;
        padding: 10px; 
        margin: 5px;   
        border: 1px solid #ccc;
}
</style>