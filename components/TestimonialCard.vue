<template>
    <div class="border border-gray-600 rounded-lg p-5 ">
        <div id="testimonial-text" v-for="paragraph in testimonial"><p class="mb-4">{{ paragraph }}</p></div>
        <br/>
        <div id="testimonial-author" class="text-bold"><span>- {{ author }}</span></div>
    </div>
</template>

<script setup lang="ts">
    const props = defineProps({
        testimonial: Array,
        author: String
    });
</script>

<style>

</style>