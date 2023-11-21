<script setup>
defineProps({
    title: {
        type: String,
        required: true
    }, 
    resume: {
        type: String,
        required: true
    }
})

</script>

<template>
    <ul>
        <li>
            {{ title }}
            <br>
                <slot name="resumo">{{ resume }}</slot>
        </li>
    </ul>

</template>

<style scoped>
</style>