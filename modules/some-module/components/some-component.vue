<template>
    <button @click="fire">
        Feature button
    </button>
</template>
<script setup>
const fire = () => window.prompt('WORK 111')
</script>