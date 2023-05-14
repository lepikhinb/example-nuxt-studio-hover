<script setup lang="ts">
import BaseCard from "./BaseCard.vue";
</script>

<template>
  <BaseCard>
    <img
      src="https://nuxt.com/assets/home/ux-hybrid-dark.svg"
      class="h-full rounded-md"
    />

    <div class="flex flex-col gap-y-4">
      <header class="font-semibold text-gray-100 text-xl">
        On-demand Rendering
      </header>

      <p class="text-gray-300 font-extralight">
        Decide what rendering strategy at the route level: SSR, SSG, CSR, ISR,
        ESR, SWR. Build any kind of website or web application with optimized
        performance in mind.
      </p>
    </div>
  </BaseCard>
</template>
