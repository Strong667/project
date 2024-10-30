<template>
  <div class="fixed top-0 left-0 h-full w-full bg-black z-10 opacity-70"></div>
  <div class="bg-white w-96 h-full fixed right-0 top-0 z-20 p-8">
    <DrawerHead />
    <CartItemList />
    <div>
      <div>
        <span> Итого: </span>
        <div></div>
        <b>12995 ₽</b>
      </div>
    </div>
  </div>
</template>

<script setup lang="ts">
import CartItemList from './CartItemList.vue'
import DrawerHead from './DrawerHead.vue'
</script>
