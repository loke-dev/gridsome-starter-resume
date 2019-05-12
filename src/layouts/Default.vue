<template>
  <div class="layout">
    <Nav/>
    <slot/>
  </div>
</template>

<script>
import Nav from "../components/Nav";

export default {
  components: {
    Nav
  }
};
</script>


<style lang="scss">
</style>
