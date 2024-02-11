<script setup>
  import Card from './Card.vue';
</script>

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
      <Card />
    </div>
  </div>
</template>
