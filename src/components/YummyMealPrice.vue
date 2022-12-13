<script setup>
import {inject, ref} from "vue";

const currencySymbol = inject('currencySymbol', ref('A default value: '));
</script>

<template>
  <span>{{ currencySymbol }}</span>
</template>

<style scoped>

</style>