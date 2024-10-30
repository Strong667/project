<template>
  <div class="grid grid-cols-4 gap-5">
    <Card
      title="Мужские Кроссовки Nike Mid Suede"
      imageUrl="/sneakers/sneakers-1.jpg"
      :price="5000"
      :isAdded="true"
      :isFavorite="true"
      :onClickAdd="onClickAdd"
      :onClickFavorite="onClickFavorite"
    />
  </div>
</template>

<script setup>
import Card from './Card.vue'

const onClickAdd = () => {
  alert('Done!')
}

const onClickFavorite = () => {
  alert('Done2!')
}
</script>
