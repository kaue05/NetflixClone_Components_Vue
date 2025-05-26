<script setup>
    import CardContRel from './CardContRel.vue';
</script>

<template>
    <h3 class="text-xl md:text-2xl font-bold mb-4">Mais como este</h3>
    <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-4">
        <CardContRel 
            alt="Sugestão+1"
            titulo="Título Sugerido 1"
            relevancia="97% relevante"
        />
        <CardContRel 
            alt="Sugestão+2"
            titulo="Título Sugerido 2"
            relevancia="95% relevante"
        />
        <CardContRel 
            alt="Sugestão+3"
            titulo="Título Sugerido 3"
            relevancia="93% relevante"
        />
        <CardContRel 
            alt="Sugestão+4"
            titulo="Título Sugerido 4"
            relevancia="97% relevante"
        />
        <CardContRel 
            alt="Sugestão+5"
            titulo="Título Sugerido 5"
            relevancia="96% relevante"
        />
        <CardContRel 
            alt="Sugestão+6"
            titulo="Título Sugerido 6"
            relevancia="94% relevante"
        />
    </div>
</template>

<style scoped>
</style>