<script setup>
import { ref } from 'vue'

const hot_games = ref([1, 2, 3, 4, 5, 6, 7, 8, 9])
</script>

<template>
  <section>
    <div class="my-4"><p class="text-bold text-amber-400">Hot Game</p></div>
    <div
      class="flex items-center gap-5 flex-grow-0 overflow-auto md:overflow-scroll"
    >
      <div
        class="flex justify-center items-center h-20 w-20 rounded-md bg-slate-200"
        v-for="(game, index) in hot_games"
        :key="game"
      >
        <p>{{ game }}</p>
      </div>
    </div>
  </section>
</template>
