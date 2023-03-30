<template>
    <div class="post-card">
        <h3>titulo</h3>
        <p>Et dolor eos lorem consetetur ipsum et sit aliquyam. Ipsum eos sit nonumy gubergren eirmod eirmod. Aliquyam ipsum et ut.</p>
        <PostButton/>
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