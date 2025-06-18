<template>
  <div class="bg-white overflow-hidden border-b border-gray-200">
    <div class="relative bg-gradient-to-br from-teal-400 to-cyan-300 aspect-video">
      <div class="absolute inset-0 flex items-center justify-center">
        <img
            src="../assets/images/player.png"
            alt="Course preview"
            class="w-full h-full object-cover"
        >
      </div>

      <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black/50 to-transparent p-4">
        <div class="flex items-center justify-between text-white">
          <div class="flex items-center space-x-4">
            <button class="p-2 hover:bg-white/20 rounded">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 19l-7-7 7-7"/>
              </svg>
            </button>

            <button class="p-3 bg-white/20 hover:bg-white/30 rounded-full">
              <svg class="w-6 h-6" fill="currentColor" viewBox="0 0 24 24">
                <path d="M8 5v14l11-7z"/>
              </svg>
            </button>

            <button class="p-2 hover:bg-white/20 rounded">
              <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 5l7 7-7 7"/>
              </svg>
            </button>
          </div>

          <div class="flex items-center space-x-4">
            <span class="text-sm">1:25 / 8:45</span>

            <button class="p-2 hover:bg-white/20 rounded">
              <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24">
                <path d="M3 9v6h4l5 5V4L7 9H3zm13.5 3c0-1.77-1.02-3.29-2.5-4.03v8.05c1.48-.73 2.5-2.25 2.5-4.02zM14 3.23v2.06c2.89.86 5 3.54 5 6.71s-2.11 5.85-5 6.71v2.06c4.01-.91 7-4.49 7-8.77s-2.99-7.86-7-8.77z"/>
              </svg>
            </button>

            <button class="p-2 hover:bg-white/20 rounded">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"/>
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"/>
              </svg>
            </button>

            <button class="p-2 hover:bg-white/20 rounded">
              <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 8V4m0 0h4M4 4l5 5m11-1V4m0 0h-4m4 0l-5 5M4 16v4m0 0h4m-4 0l5-5m11 5l-5-5m5 5v-4m0 4h-4"/>
              </svg>
            </button>
          </div>
        </div>

        <div class="mt-2">
          <div class="w-full bg-white/30 rounded-full h-1">
            <div class="bg-white h-1 rounded-full" style="width: 15%"></div>
          </div>
        </div>
      </div>
    </div>

    <div class="p-6">
      <h2 class="text-2xl font-bold text-gray-900 mb-4">2. Sign up in Webflow</h2>

      <div class="flex justify-between items-center space-x-4 mb-2">
        <div class="flex items-center">
          <div class="flex -space-x-1">
            <div class="w-8 h-8 bg-yellow-400 rounded-full border-2 border-white"></div>
            <div class="w-8 h-8 bg-red-400 rounded-full border-2 border-white"></div>
            <div class="w-8 h-8 bg-green-400 rounded-full border-2 border-white"></div>
            <div class="w-8 h-8 bg-blue-400 rounded-full border-2 border-white"></div>
            <div class="w-8 h-8 bg-purple-400 rounded-full border-2 border-white"></div>
          </div>
          <div class="flex flex-col ml-2">
            <span class="text-sm font-medium">512</span>
            <span class="text-sm text-gray-500">Students watching</span>
          </div>
        </div>

        <div class="flex space-x-4">
          <div class="text-sm text-gray-500">
            Last updated: <span class="text-gray-900">Oct 28, 2020</span>
          </div>

          <div class="text-sm text-gray-500">
            Comments: <span class="text-gray-900">154</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script setup lang="ts">
</script>