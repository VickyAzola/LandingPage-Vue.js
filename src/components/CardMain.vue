<script setup>
    defineProps({
        img: String,
        title: String,
        description: String,
    })
</script>

<template>
    <div class="p-6 shadow rounded-md mx-4 lg:mx-20 my-10 lg:grid lg:grid-cols-2 lg:items-center">
        <img :src=img alt="Illustration" class="lg:max-w-[28rem] lg:m-auto lg:pr-4 lg:order-last"/>
        <div class="text-center lg:text-left py-4 lg:px-10">
            <h2 class="my-3 text-2xl font-bold text-[#00252e]">{{ title }}</h2>
            <p class="text-[#808d99] lg:mr-10">{{ description }}</p>
        </div>
    </div>
</template>
