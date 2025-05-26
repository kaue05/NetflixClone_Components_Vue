<script setup>
    defineProps({
        pagina_ativa: {
            type: String,
            required: true,
        }
    })
</script>

<template>
    <!-- Menu Topo -->
    <div class="container mx-auto px-4 py-4 flex items-center justify-between">
        <div class="flex items-center">
            <h1 class="text-netflix-red text-3xl font-bold mr-10">NETFLIXCLONE</h1>
            <nav class="hidden md:block">
                <ul class="flex space-x-6">
                    <li><a href="#" class="text-white font-medium">Início</a></li>
                    <li><a href="#" class="text-netflix-light/80 hover:text-white">Séries</a></li>
                    <li><a href="#" class="text-netflix-light/80 hover:text-white">Filmes</a></li>
                    <li><a href="#" class="text-netflix-light/80 hover:text-white">Bombando</a></li>
                    <li><a href="#" class="text-netflix-light/80 hover:text-white">Minha lista</a></li>
                </ul>
            </nav>
        </div>
        <div class="flex items-center space-x-4">
            <button class="text-white">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
                </svg>
            </button>
            <button class="text-white">
                <svg xmlns="http://www.w3.org/2000/svg" class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 17h5l-1.405-1.405A2.032 2.032 0 0118 14.158V11a6.002 6.002 0 00-4-5.659V5a2 2 0 10-4 0v.341C7.67 6.165 6 8.388 6 11v3.159c0 .538-.214 1.055-.595 1.436L4 17h5m6 0v1a3 3 0 11-6 0v-1m6 0H9" />
                </svg>
            </button>
            <div class="relative">
                <img src="https://placehold.co/32" alt="Perfil" class="rounded">
            </div>
        </div>
    </div>
</template>

<style scoped>

</style>