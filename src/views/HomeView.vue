<script setup>
  import MenuPrincipal from '@/components/Menu.vue';
  import HeroSection from '@/components/HeroSection.vue';
  import FooterHome from '@/components/Footer.vue';
  import ListaHome from '@/components/ListaHome.vue';
</script>

<template>
  <header class="fixed top-0 w-full z-50 transition-all duration-500 bg-gradient-to-b from-black/80 to-transparent">
    <MenuPrincipal pagina_ativa="/"/>
  </header>

  <section class="relative h-screen">
    <HeroSection />
  </section>

  <section class="py-6 px-4 md:px-16">
    <ListaHome 
      titulo="Populares na Netflix",
      card="CardFilme"/>
  </section>

  <section class="py-6 px-4 md:px-16">
    <ListaHome 
      titulo="Séries em alta",
      card="CardEmAlta"/>
  </section>

  <section class="py-6 px-4 md:px-16">
    <ListaHome 
      titulo="Originais NetFlix",
      card="CardOriginal"/>
  </section>

  <footer class="py-10 px-4 md:px-16 text-netflix-gray">
    <FooterHome />
  </footer>

</template>

<style scoped>
</style>