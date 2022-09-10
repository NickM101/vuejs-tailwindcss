<script setup>
import Carousel from './components/Carousel.vue'
import Container from './components/Container.vue'
import Poster from './components/Poster.vue'
</script>

<template>
  <div class="flex flex-col min-h-screen md:px-3 lg:px-5">
    <header class="mx-3">
      <nav class="flex justify-between items-center h-14">
        <img src="../images/ho_me.png" />

        <img src="../images/ho_lo.png" />

        <img src="../images/ho_li.png" />
      </nav>
      <section class="">
        <div class="rounded-md h-40 md:h-56 bg-slate-300"></div>
      </section>
    </header>
    <main class="px-3">
      <carousel />
      <poster />
      <container />
    </main>
    <footer class="w-full h-14 bg-gray-900 fixed left-0 bottom-0">
      <nav class="flex justify-between px-4 py-4 lg:px-10">
        <img src="../images/ho_ho1.png" />

        <img src="../images/ho_ac2.png" />

        <img src="../images/ho_wa2.png" />
        <img src="../images/ho_co2.png" />
        <img src="../images/ho_my2.png" />
      </nav>
    </footer>
  </div>
</template>

<style scoped></style>
