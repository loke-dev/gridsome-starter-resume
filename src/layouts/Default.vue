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
body {
  font-family: "Muli", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto,
    "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji",
    "Segoe UI Symbol", "Noto Color Emoji";
  padding-top: 54px;
  color: #868e96;
}

@media (min-width: 992px) {
  body {
    padding-top: 0;
    padding-left: 17rem;
  }
}

h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: "Saira Extra Condensed", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-weight: 700;
  text-transform: uppercase;
  color: #343a40;
}

h1 {
  font-size: 6rem;
  line-height: 5.5rem;
}

h2 {
  font-size: 3.5rem;
}

h3 {
  font-size: 2rem;
}

p.lead {
  font-size: 1.15rem;
  font-weight: 400;
}
</style>
