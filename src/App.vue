<script setup>
import Carousel from './components/Carousel.vue'
import Banner from './components/Banner.vue'
import Container from './components/Container.vue'
</script>

<template>
  <div class="flex flex-col min-h-screen">
    <header class="bg-indigo-600 h-14">
      <nav class="flex justify-between items-center px-4 py-2">
        <img src="./assets/images/ho_me.png" />

        <img src="./assets/images/ho_lo.png" />

        <img src="./assets/images/ho_li.png" />
      </nav>
    </header>
    <main class="bg-amber-500 px-3">
      <banner />
      <carousel />
      <container />
    </main>
    <footer class="bg-red-900 h-14 sticky top-[100vh]">
      <nav class="flex justify-between px-4 py-4">
        <img src="./assets/images/ho_ho1.png" />

        <img src="./assets/images/ho_ac2.png" />

        <img src="./assets/images/ho_wa2.png" />
        <img src="./assets/images/ho_co2.png" />
        <img src="./assets/images/ho_my2.png" />
      </nav>
    </footer>
  </div>
</template>

<style scoped></style>
