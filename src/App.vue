<script setup>
import IButton from './components/IButton/IButton.vue'
const classes = {
  bgcolor: false
}
</script>
<template>
  <span class="btn"> Hello span</span>
  Hello vue <IButton :class="classes"></IButton>
</template>

<style>
.bgcolor {
  background-color: bisque;
}
</style>
