<template>
<div>

  <div>This is <Count :count="currentCount" /></div>
  cc = {{ currentCount }}
</div>
</template>

<script>
import Count from "./Count.vue";

export default {
  components: {
    Count,
  },
  props: {
    currentCount: Number,
  },
};
</script>