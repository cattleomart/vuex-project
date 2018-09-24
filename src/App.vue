<template>
  <div id="app">
   <product-list-one >
     
   </product-list-one>
   <product-list-two></product-list-two>
  </div>
</template>

<script>
import ProductListOne from "./components/productListOne.vue";
import ProductListTwo from "./components/productListTwo.vue";

export default {
  name: "app",

  components: {
    "product-list-one": ProductListOne,
    "product-list-two": ProductListTwo
  },
  data() {
    return {};
  }
};
</script>


<style lang="scss">
</style>
