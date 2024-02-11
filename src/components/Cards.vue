<template>
  <div class="container px-10">
    <div class="flex justify-between items-center pb-5">
      <h2 class="font-bold text-3xl">Все кроссовки</h2>
      <div class="flex gap-5 items-center">
        <select>
          <option value="Максимальная цена">Макс цена...</option>
          <option value="Минимальная цена">Мин цена...</option>
        </select>
        <input
          type="search"
          placeholder="Поиск"
          class="border rounded-md p-1 outline-none"
        />
      </div>
    </div>
    <div class="flex flex-wrap py-5 justify-between">
      <div
        class="border p-5 rounded-xl w-64 shadow-md transition-all hover:-translate-y-2"
      >
        <img src="../public/heart.svg" alt="favorites" class="cursor-pointer" />
        <img
          src="../public/sneakers/sneakers-1.jpg"
          alt="sneakers photo"
          class="w-36 mx-auto"
        />
        <p>Мужские кроссовки Nike Blazer Mid Suede</p>
        <div class="flex justify-between items-start mt-2">
          <ul class="flex flex-col items-start">
            <li><span class="text-gray-500">Цена:</span></li>
            <li><p class="font-bold">12 999 руб.</p></li>
          </ul>
          <img src="../public/plus.svg" alt="Plus" class="cursor-pointer" />
        </div>
      </div>
    </div>
  </div>
</template>
