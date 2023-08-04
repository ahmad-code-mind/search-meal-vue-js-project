<template>
    <pre>{{ meals }}</pre>
</template>

<script setup>
import { computed } from 'vue';
import store from '../store/store.js'

const meals = computed(() => store.state.meals);

</script>

<style scoped>
</style>