<script setup>
    defineProps({
        titulo: String,
        conteudo: String,
        dataPublicacao: String,
        url: {
            type: String,
            default: "/"
        },
    })
</script>

<template>
    <RouterLink :to="url">
        <article class="bg-gray-200 shadow-md rounded-lg p-4">
            <h4 class="text-xl font-semibold"><slot>{{ titulo }}</slot></h4>
            <p class="text-gray-600"><slot>{{ conteudo }}</slot></p>
            <p class="text-gray-500 text-sm mt-2"><slot>{{ dataPublicacao }}</slot></p>
        </article>
    </RouterLink>
</template>

<style scoped>

</style>