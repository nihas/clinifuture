<template>
  <header class="fixed top-0 left-0 w-full z-50 bg-white backdrop-blur-md">
    <nav class="max-w-7xl mx-auto px-4 py-4 flex items-center justify-between">
      
      <!-- Logo -->
      <div class="flex items-center text-black text-xl font-bold">
        <img src="/clinifuture_logo.png" alt="Tek-Z Logo" class="h-8 mr-2">
        CLINI<span class="text-indigo-400">FUTURE</span>
      </div>

      <!-- Desktop Menu -->
      <ul class="hidden md:flex space-x-8 text-black font-medium">
        <li class="hover:text-indigo-400 cursor-pointer">Home</li>
        <li class="hover:text-indigo-400 cursor-pointer">About Us</li>
        <li class="hover:text-indigo-400 cursor-pointer">Courses</li>
        <li class="hover:text-indigo-400 cursor-pointer">Contact Us</li>
      </ul>

      <!-- Mobile Menu Button -->
      <button
        class="md:hidden text-white"
        @click="isOpen = !isOpen"
      >
        <svg xmlns="http://www.w3.org/2000/svg" class="h-7 w-7" fill="none"
          viewBox="0 0 24 24" stroke="currentColor">
          <path stroke-linecap="round" stroke-linejoin="round"
            stroke-width="2"
            d="M4 6h16M4 12h16M4 18h16" />
        </svg>
      </button>
    </nav>

    <!-- Mobile Menu -->
    <div v-if="isOpen" class="md:hidden bg-black/90 text-white px-6 pb-6">
      <ul class="space-y-4 font-medium">
        <li>Home</li>
        <li>About Us</li>
        <li>Courses</li>
        <li>Contact Us</li>
      </ul>
    </div>
  </header>
</template>

<script setup>
import { ref } from 'vue'
const isOpen = ref(false)
</script>