<script setup lang="ts">
//
</script>

<template>
  <div
    class="border-gradient group relative transition rounded-xl border-[#272725] border before:absolute before:-inset-px before:h-[calc(100%+2px)] before:w-[calc(100%+2px)] before:rounded-xl"
  >
    <div
      class="absolute inset-0 rounded-[11px] bg-[#18181B] transition-colors duration-300 group-hover:bg-[#272725]"
    ></div>

    <div class="relative p-6">
      <slot />
    </div>
  </div>
</template>

<style>
.border-gradient:hover::before {
  animation: gradient-rotate 5s linear 0s infinite reverse;
  opacity: 1;
  transition: opacity cubic-bezier(0.4, 0, 0.2, 1) 1000ms;
}

.border-gradient::before {
  opacity: 0;
  background: linear-gradient(
    var(--gradient-angle),
    hsla(0, 0%, 100%, 0.5),
    hsla(0, 0%, 100%, 0.1),
    #fff,
    hsla(0, 0%, 100%, 0.3)
  );
}

@property --gradient-angle {
  syntax: "<angle>";
  inherits: false;
  initial-value: 1turn;
}

@keyframes gradient-rotate {
  0% {
    --gradient-angle: 360deg;
  }
  to {
    --gradient-angle: 0deg;
  }
}
</style>
