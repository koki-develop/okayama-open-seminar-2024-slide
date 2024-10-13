<template>
  <button
    class="text-lg fixed rounded-l bottom-10 flex items-center gap-2 right-0 bg-black/70 hover:bg-black/90 transition-colors transition text-white px-4 py-2"
    @click="$nav.next"
  >
    <span>スキップ</span>
    <carbon:skip-forward-filled />
  </button>
</template>
