<template>
    <div class="border border-gray-600 rounded-lg p-5 ">
        <div id="testimonial-text">{{ testimonial }}</div>
        <br/>
        <div id="testimonial-author" class="text-bold"><span>- {{ author }}</span></div>
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