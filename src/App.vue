<script setup>
import { ref } from 'vue'
const num = ref(5)
function clickMe() {
  num.value++
}
</script>

<template>
  <div>
    {{ num }}
    <button type="button" v-on:click="clickMe">click me</button>
  </div>
</template>
