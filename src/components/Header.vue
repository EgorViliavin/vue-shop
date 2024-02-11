<template>
  <header class="container mx-auto p-10 border-b-2 mb-5">
    <div class="flex justify-between items-center">
      <div class="flex gap-3 items-center">
        <img src="../public/logo.png" alt="Logo" class="w-12 h-12" />
        <div>
          <h1 class="font-bold text-2xl uppercase">Sneakers SHop</h1>
          <p class="text-md text-gray-400">Магазин лучших кроссовок</p>
        </div>
      </div>
      <div>
        <ul class="flex">
          <li class="flex items-center gap-1 mr-4 cursor-pointer">
            <img src="../public/cart.svg" alt="cart icon" />
            <p class="text-sm text-gray-500 hover:text-gray-900 transition-all">
              1205 руб
            </p>
          </li>
          <li class="flex items-center gap-1 mr-4 cursor-pointer">
            <img src="../public/heart.svg" alt="favorites icon" />
            <p class="text-sm text-gray-500 hover:text-gray-900 transition-all">
              Закладки
            </p>
          </li>
          <li class="flex items-center gap-1 mr-4 cursor-pointer">
            <img src="../public/profile.svg" alt="profile icon" />
            <p class="text-sm text-gray-500 hover:text-gray-900 transition-all">
              Профиль
            </p>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>
