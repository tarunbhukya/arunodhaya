<template>
    <div class="w-full h-full rounded border-gray-100 border-2 p-4 text-white" v-bind:style="{ backgroundColor: color }">
        <p class="text-center text-2xl">{{title}}</p>
        <p class="mt-4 text-lg line-clamp-2">{{ content }}</p>
        <a :href="url">View More</a>
    </div>
</template>

<script setup>
 defineProps({
  color: String,
  title: String,
  content: String,
  url: String,
})
</script>

