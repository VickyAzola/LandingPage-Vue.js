<script setup>
    defineProps({
        text : String
    })
</script>

<template>
    <button type="button" class="bg-[#ff52bf] px-8 py-3 text-white rounded-full font-bold text-sm shadow-md
    hover:bg-[#f997d5]">
        {{ text }}
    </button>
</template>


