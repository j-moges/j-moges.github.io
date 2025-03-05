<template>
    <div class="border-amber-600 rounded-lg">
        <div id="testimonial-text">{{ testimonial }}</div>
        <div id="testimonial-author">{{ author }}</div>
    </div>
</template>

<script setup>
    const props = defineProps({
        testimonial: String,
        author: String
    });
</script>

<style>

</style>