<template>
    <div class="w-full h-full rounded-xl border-gray-100 border-2 p-4 text-white" v-bind:style="{ backgroundColor: color }">
        <p class="text-center text-2xl">{{title}}</p>
        <p class="mt-4 mb-4 text-lg line-clamp-6">{{ content }}</p>
        <NuxtLink class="pt-4 cursor-pointer" :to="url">View More</NuxtLink>
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

