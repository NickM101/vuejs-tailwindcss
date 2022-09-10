<template>
  <section>
    <div class="my-3"><p class="text-bold text-amber-400">Hot Game</p></div>
    <div class="flex items-center gap-5 overflow-x-auto h-20">
      <div
        class="flex flex-shrink-0 justify-center items-center h-20 md:h-24 w-36 md:w-24 rounded-md bg-slate-200"
        v-for="(game, index) in Array(25)"
        :key="game"
      >
        <p>{{ game }}</p>
      </div>
    </div>
  </section>
</template>
