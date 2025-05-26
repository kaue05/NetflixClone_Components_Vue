<script setup>
    import CardFilme from './CardFilme.vue';
    import CardEmAlta from './CardEmAlta.vue';
    import CardOriginal from './CardOriginal.vue';

    const components = {
        CardFilme,
        CardEmAlta,
        CardOriginal
    }

    defineProps({
        titulo: String,
        card: String
    })

</script>

<template>
    <h3 class="text-xl md:text-2xl font-bold mb-4">{{ titulo }}</h3>
    <div class="flex overflow-x-scroll scrollbar-hide space-x-4 pb-4 justify-center">
        <component
            v-for="i in 5"
            :key="i"
            :is="components[card]"
            url="/assistir"
        />
    </div>
</template>

<style scoped>
</style>