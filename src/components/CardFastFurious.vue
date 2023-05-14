<script setup lang="ts">
import BaseCard from "./BaseCard.vue";
</script>

<template>
  <BaseCard>
    <img
      src="https://nuxt.com/assets/home/ux-fast-dark.svg"
      class="h-full rounded-md"
    />

    <div class="flex flex-col gap-y-4">
      <header class="font-semibold text-gray-100 text-xl">
        Fast and Furious
      </header>

      <p class="text-gray-300 font-extralight">
        Optimized with code-splitting, tree-shaking, optimized cold-start, link
        prefetching, payload extraction, just to name a few. Fast by default so
        you can focus on building.
      </p>
    </div>
  </BaseCard>
</template>
