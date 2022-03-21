<template>
  <div>
    <!-- <div>This is APP</div>
    <Header :currentCount="count" />
    <Main :incFn="inc" /> -->
    <ProductList />
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Main from "./components/Main.vue";
import ProductList from "./components/ProductList.vue"

export default {
  components: {
    Header,
    Main,
    ProductList,
  },
  data() {
    return {
      count: 0,
    };
  },
  methods: {
    inc() {
      this.count++;
    },
  },
};
</script>
