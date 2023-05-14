<script setup lang="ts">
import BaseCard from "./BaseCard.vue";
</script>

<template>
  <BaseCard>
    <img
      src="https://nuxt.com/assets/home/ux-seo-dark.svg"
      class="h-full rounded-md"
    />

    <div class="flex flex-col gap-y-4">
      <header class="font-semibold text-gray-100 text-xl">
        SEO & Web Vitals
      </header>

      <p class="text-gray-300 font-extralight">
        By leveraging server-side rendering, ESM format and optimized images,
        Nuxt websites are indexable by search engines while giving the feeling
        of an app to the end-users.
      </p>
    </div>
  </BaseCard>
</template>
