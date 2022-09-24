<template>
  <p></p>
</template>
<script>
import { ref } from 'vue';
export default {
  name: 'Todex',
  setup() {
    const todos = ref(['Viec 1', 'Viec 2', 'Viec 3']);
    return {
      todos,
    };
  },
};
</script>
<style></style>
