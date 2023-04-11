<template>
  <p v-bind:style="{ backgroundColor: 'red', color: c }">
    El mensaje se ha enviado satisfactoriamente.
  </p>
  <button v-on:click="handleClick()">Cambiar color</button>
</template>

<script lang="ts" setup>
import { ref } from "vue";
let c = ref("#fff");
const handleClick = () => {
  c.value = "orange";
};
</script>

<style></style>
