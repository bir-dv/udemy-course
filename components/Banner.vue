<template>
  <div v-if="showBanner" class="relative bg-[#5637D5] text-white">
    <div class="w-full mx-auto px-6 py-3 flex items-center justify-center gap-2">
      <span>Ready to get with the times?</span>
      <a href="#" class="underline hover:no-underline">Get the skills with Udemy Business.</a>
      
      <!-- Close button -->
      <button 
        @click="$emit('close')" 
        class="absolute right-6 top-1/2 -translate-y-1/2 p-1 hover:opacity-80"
      >
        <svg 
          xmlns="http://www.w3.org/2000/svg" 
          class="h-5 w-5" 
          viewBox="0 0 20 20" 
          fill="currentColor"
        >
          <path 
            fill-rule="evenodd" 
            d="M4.293 4.293a1 1 0 011.414 0L10 8.586l4.293-4.293a1 1 0 111.414 1.414L11.414 10l4.293 4.293a1 1 0 01-1.414 1.414L10 11.414l-4.293 4.293a1 1 0 01-1.414-1.414L8.586 10 4.293 5.707a1 1 0 010-1.414z" 
            clip-rule="evenodd" 
          />
        </svg>
      </button>
    </div>
  </div>
</template>

<script setup>
defineEmits(['close'])
defineProps({
  showBanner: {
    type: Boolean,
    default: true
  }
})
</script> 