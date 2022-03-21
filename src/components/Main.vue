<template>
  <button @click="incFn">Click me</button>
</template>

<script>
export default {
  props: {
    incFn: Function,
  },
};
</script>