<script setup>
    defineProps({
        url: {
            type: String,
            default: "/"
        }
    })
</script>

<template>
    <RouterLink :to="url">
        <div class="movie-card flex-none w-[180px] transition-transform duration-300 relative">
            <img src="https://placehold.co/180x270/000000/FFFFFF?text=Filme+1" alt="Filme 1" class="rounded-md w-full">
            <div class="movie-info absolute inset-0 bg-gradient-to-t from-black to-transparent rounded-md p-4 flex flex-col justify-end opacity-0 transition-opacity duration-300">
                <h4 class="font-bold">Filme 1</h4>
                <div class="flex items-center text-xs mt-1">
                    <span class="text-green-500 font-bold">97% relevante</span>
                    <span class="mx-2 border border-white/40 px-1">16</span>
                    <span>2023</span>
                </div>
            </div>
        </div> 
    </RouterLink>
</template>

<style scoped>
</style>