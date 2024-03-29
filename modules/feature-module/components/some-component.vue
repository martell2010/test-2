<template>
    <button @click="fire" class="test">
        Feature two button
    </button>
</template>
<script setup>
const fire = () => window.prompt('WORK')
</script>