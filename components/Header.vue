<template>
  <header class="border-b border-gray-200">
    <div class="w-full mx-auto px-6 h-[72px] flex items-center gap-4">
      <!-- Logo -->
      <a href="/" class="flex-shrink-0">
        <img src="/images/logo.png" alt="Udemy" class="w-[104px] h-[34px]" />
      </a>

      <!-- Explore button -->
      <button class="text-sm hover:text-purple-600">
        Explore
      </button>

      <!-- Search bar -->
      <div class="relative flex-grow">
          <div class="relative">
            <div class="absolute inset-y-0 left-0 pl-4 flex items-center pointer-events-none">
              <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 text-gray-400" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z" />
              </svg>
            </div>
            <input 
              type="text" 
              placeholder="Search for anything" 
              class="w-full py-[11px] pl-12 pr-4 border border-black rounded-[9999px] focus:outline-none focus:ring-1 focus:ring-purple-600"
            >
          </div>
        </div>
      <!-- Navigation -->
      <Navigation />
    </div>
  </header>
</template>

<script setup>
import Navigation from './Navigation.vue'
</script> 