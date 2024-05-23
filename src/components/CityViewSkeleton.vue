<template>
    <div class="flex flex-col flex-1">
        <div class="flex flex-col items-center py-12">
            <AnimatedPlaceholder class="max-w-[300px] w-full mb-2"/>
            <AnimatedPlaceholder class="max-w-[300px] w-full mb-12"/>
            <AnimatedPlaceholder class="max-w-[300px] h-[100px] w-full mb-12"/>
            <AnimatedPlaceholder class="max-w-[300px] w-full mb-8"/>                <AnimatedPlaceholder class="max-w-[300px] h-[75px] w-full"/>
        </div>

        <hr class="border-white border-opacity-10 border w-full" />
    </div>
</template>

<script setup>
import AnimatedPlaceholder from "./AnimatedPlaceholder.vue";
</script>
