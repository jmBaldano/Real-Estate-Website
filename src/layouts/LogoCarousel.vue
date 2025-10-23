<template>
  <div class="relative w-full py-6 overflow-hidden bg-white">
    <div
      class="flex animate-scroll"
      :style="{ animationDuration: speed + 's' }"
      ref="carousel"
    >
      <!-- Repeat logos to fill screen and allow infinite scroll -->
      <div
        v-for="n in repeatCount"
        :key="n"
        class="flex gap-100"
        :class="n !== 1 ? 'ml-150' : ''"
      >
        <img
          v-for="(logo, index) in logos"
          :key="index + '-' + n"
          :src="logo"
          alt="Logo"
          class="flex-shrink-0 object-contain h-16"
        />
      </div>
    </div>
  </div>
</template>


<script setup>
import { ref, onMounted } from 'vue'

const props = defineProps({
  logos: {
    type: Array,
    required: true
  },
  speed: {
    type: Number,
    default: 30 // seconds for full scroll
  }
})

const repeatCount = ref(2)

onMounted(() => {
  // Calculate repeats so that 4 logos fill the width + gaps
  const screenWidth = window.innerWidth
  const logoWidth = 120 // estimated width per logo in px
  const gap = 64 // Tailwind gap-16 = 4rem = 64px
  const totalLogoWidth = props.logos.length * (logoWidth + gap)
  repeatCount.value = Math.ceil(screenWidth / totalLogoWidth) + 2
})
</script>

<style>
@keyframes scroll {
  0% { transform: translateX(0); }
  100% { transform: translateX(-50%); }
}

.animate-scroll {
  display: flex;
  animation-name: scroll;
  animation-timing-function: linear;
  animation-iteration-count: infinite;
}
</style>
