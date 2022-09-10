<script setup>
import { ref } from 'vue'

const side_nav = ref([
  {
    id: 1,
    name: 'Used',
    image: 'ho_us1@3x.png'
  },
  {
    id: 2,
    name: 'Live',
    image: 'ho_li2@3x.png'
  },
  {
    id: 3,
    name: 'Sport',
    image: 'ho_sp2@3x.png'
  },
  {
    id: 4,
    name: 'Lottery',
    image: 'ho_lo2@3x.png'
  },
  {
    id: 5,
    name: 'Poker',
    image: 'ho_po2@3x.png'
  },
  {
    id: 6,
    name: 'Game',
    image: 'ho_ga2@3x.png'
  }
])
</script>
<template>
  <section class="grid grid-flow-col">
    <div class="flex flex-col col-span-1">
      <img
        v-for="item in side_nav"
        class="h-14 md:h-20 w-14 md:w-20 rounded my-1"
        v-bind:src="'../images/' + item.image"
        :alt="item.name"
        :key="item.id"
      />
    </div>
    <div class="flex flex-col col-span-12 mt-1">
      <div
        v-for="i in Array(4)"
        class="mb-4 h-20 md:h-28 w-full bg-slate-200 rounded-md"
      ></div>
    </div>
  </section>
</template>
