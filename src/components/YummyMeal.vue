<script setup>

const props = defineProps({
  name: {
    type: String,
    required: true
  },
  price: {
    type: Number,
    required: true
  }
});

const emit = defineEmits(['addToCart'])

const addToCart = () => emit('addToCart', props.name);

</script>

<template>
  <div>
    <h1>{{ props.name }}</h1>
    <p>${{ props.price }}</p>
    <button @click="addToCart" >Add to cart</button>
  </div>
</template>

<style lang="scss" scoped>

</style>