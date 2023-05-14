<script setup lang="ts">
import CardFastFurious from "./components/CardFastFurious.vue";
import CardOnDemand from "./components/CardOnDemand.vue";
import CardSeo from "./components/CardSeo.vue";
</script>

<template>
  <div
    class="relative flex h-screen w-screen items-center justify-center bg-[#0d0d0e]"
  >
    <div class="max-w-7xl w-full p-12">
      <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-8">
        <CardFastFurious />

        <CardOnDemand />

        <CardSeo />
      </div>
    </div>
  </div>
</template>
