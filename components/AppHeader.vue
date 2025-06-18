<template>
  <div class="bg-[#1D2026] text-[14px] antialiased">
    <nav class="text-gray-500 p-4 shadow-md">
      <div class="px-8 flex justify-between items-center">
        <div class="flex space-x-10">
          <a href="#" class="text-white">Главная</a>
          <a href="#">Курсы</a>
          <a href="#">Подписки</a>
          <a href="#">Мероприятия</a>
        </div>
        <div class="flex items-center space-x-6">
          <div class="relative">
            <select class="border-none focus:ring-0 focus:outline-none cursor-pointer">
              <option>Инструктор</option>
              <option>...</option>
            </select>
          </div>
          <div class="relative">
            <select class=" border-none focus:ring-0 focus:outline-none cursor-pointer">
              <option>Русский</option>
              <option>English</option>
            </select>
          </div>
        </div>
      </div>
    </nav>
    <header class="bg-white py-6 px-8">
      <div class="flex items-center justify-between px-4">
      <div class="flex items-center">
        <div class="pr-8">
          <img src="../assets/images/logo.svg" alt="logo">
        </div>

        <div class="flex items-center space-x-4 flex-grow max-w-xl ml-12">
          <div class="relative w-48">
            <div class="w-50 h-12 flex justify-between items-center border border-gray-300 px-6">
              <span class="text-gray-600">Категория</span>
              <img class="w-4 h-4" src="../assets/images/CaretDown.svg" alt="arrow">
            </div>
          </div>
          <div class="relative flex-grow">
            <input
                type="text"
                placeholder="Поиск"
                class="block w-100 h-12 pl-12 px-5 border border-gray-300 bg-white placeholder-gray-500 focus:outline-none focus:ring-indigo-500 focus:border-indigo-500 sm:text-sm"
            />
            <div class="absolute inset-y-0 left-0 pl-3 flex items-center pointer-events-none">
              <img src="../assets/images/MagnifyingGlass.svg" alt="search">
            </div>
          </div>
        </div>
      </div>

        <div class="flex items-center space-x-6">
          <div class="flex space-x-6">
            <img src="../assets/images/Bell.svg" alt="">
            <img src="../assets/images/Heart.svg" alt="">
            <img src="../assets/images/ShoppingCartSimple.svg" alt="">
          </div>

          <div class="w-10 h-10 rounded-full overflow-hidden border-gray-300">
            <img
                src="../assets/images/Avatar.png"
                alt="User Avatar"
                class="w-full h-full object-cover"
            />
          </div>
        </div>
      </div>
    </header>
  </div>
</template>
<script setup lang="ts">
</script>