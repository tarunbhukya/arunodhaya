<template>
    <div class=" flex flex-col md:flex-row p-4 my-6 bg-white border-2 rounded-xl border-gray-100">
        <div class="w-full md:w-1/3">
            <div class="w-full rounded-lg overflow-hidden h-[18rem] bg-slate-50">
                <img class="object-contain w-full" :src="url" />
            </div>
        </div>
        <div class="w-full md:w-2/3 px-4 md:px-12 py-4 md:py-0 flex flex-col m-auto">
            <p class="text-2xl">{{ title }}</p>
            <p class="text-lg mt-4" v-html="content"></p>
        </div>
    </div>
</template>

<script setup>
defineProps({
    title: String,
    content: String,
    url: String,
})
</script>