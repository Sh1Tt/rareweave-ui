<template>
    <div class="absolute z-20 flex flex-col items-center justify-center w-full h-full">
        <div class="flex flex-col items-center justify-center">
            {{ message }}
        </div>
    </div>
</template>
<script setup>
    const { message } = defineProps([
        "message"
    ]);
</script>