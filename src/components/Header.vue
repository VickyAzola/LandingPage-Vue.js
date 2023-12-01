<script setup>
import Logo from '/images/logo.svg'
</script>

<template>

    <header class="flex items-center justify-between p-4 lg:py-12 lg:px-16">
        <img class="w-28 lg:w-40" :src="Logo" alt="Logo Huddle"/>
        <button type="button" class="text-sm font-bold text-[#00252e] bg-white shadow-md rounded-full px-4 py-1 lg:px-10 lg:py-2.5
        hover:text-[#808d99]">
            Try It Free
        </button>
    </header>
    
</template>

