<template>
  <fragment>
    <h4>Your Balance</h4>
    <h1 id="balance">${{ total }}</h1>
  </fragment>
</template>

<script setup>
import { defineProps } from "vue";

const props = defineProps({
  total: {
    type: Number,
    required: true,
  },
});
</script>
