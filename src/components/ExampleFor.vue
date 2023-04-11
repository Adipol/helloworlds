<template>
  <ul>
    <li v-for="country in countries" v-bind:key="country.code">
      {{ country.name }}
    </li>
  </ul>
</template>

<script lang="ts" setup>
import { Ref, ref } from "vue";

interface ICountry {
  code: string;
  name: string;
}

let countries: Ref<Array<ICountry>> = ref([
  {
    code: "es",
    name: "spain",
  },
  {
    code: "en",
    name: "UK",
  },
  {
    code: "pt",
    name: "portugal",
  },
]);
</script>

<style scoped></style>
