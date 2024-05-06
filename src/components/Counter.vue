<script setup lang="ts">
import { ref } from 'vue';
const counter = ref<number>(0);
</script>

<template>

    <span class="text-yellow-300 text-xl mr-4">{{ counter }}</span>

    <button class="border px-4 py-2 text-xl" @click="counter++">
        +
    </button>

    <button class="border px-4 py-2 text-xl" @click="counter--">
        -
    </button>

</template>

<style scoped>

</style>