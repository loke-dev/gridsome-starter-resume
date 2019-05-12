<template>
  <nav class="navbar navbar-expand-lg navbar-dark bg-primary fixed-top" id="sideNav">
    <div class="navbar-brand" v-on:click.prevent="$scrollTo('#about')">
      <span class="d-block d-lg-none">Loke Carlsson</span>
      <span class="d-none d-lg-block">
        <g-image
          alt="Image of Loke"
          src="../assets/images/profile.png"
          class="img-fluid img-profile rounded-circle mx-auto mb-2"
        />
      </span>
    </div>
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#about')">About</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#experience')">Experience</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#education')">Education</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#skills')">Skills</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#interests')">Interests</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" v-on:click.prevent="$scrollTo('#awards')">Awards</a>
        </li>
      </ul>
    </div>
  </nav>
</template>

<style scoped lang="scss">
.navbar-brand,
.nav-item {
  cursor: pointer;
}
</style>
