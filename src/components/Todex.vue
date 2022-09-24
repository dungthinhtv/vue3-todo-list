<template>
  <p v-for="todo in todos" v-bind:key="todo">{{ todo }}</p>
</template>
<script>

export default {
  name: 'Todex',
  setup() {
    const todos = ['Viec 1', 'Viec 2', 'Viec 3'];
    return {
      todos,
    };
  },
};
</script>
<style></style>
