<template>
  <b-navbar
    toggleable="lg"
    type="dark"
    variant="primary"
    fixed="top"
    id="sideNav"
    v-b-scrollspy:nav-scroller
  >
    <b-navbar-brand href="#about" @click="scrollIntoView">
      <span class="d-block d-lg-none">Loke Carlsson</span>
      <span class="d-none d-lg-block">
        <g-image
          alt="Image of Loke"
          src="../assets/images/profile.png"
          class="img-fluid img-profile rounded-circle mx-auto mb-2"
        />
      </span>
    </b-navbar-brand>
    <b-navbar-toggle target="navbar-collapse"></b-navbar-toggle>
    <b-collapse id="navbar-collapse" is-nav>
      <b-navbar-nav>
        <b-nav-item href="#about" @click="scrollIntoView"
          >About</b-nav-item
        >
        <b-nav-item
          href="#experience"
          @click="scrollIntoView"
          >Experience</b-nav-item
        >
        <b-nav-item
          href="#education"
          @click="scrollIntoView"
          >Education</b-nav-item
        >
        <b-nav-item href="#skills" @click="scrollIntoView"
          >Skills</b-nav-item
        >
        <b-nav-item
          href="#interests"
          @click="scrollIntoView"
          >Interests</b-nav-item
        >
        <b-nav-item href="#awards" @click="scrollIntoView"
          >Awards</b-nav-item
        >
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>

  
</template>

<script>
export default {
  methods: {
    scrollIntoView(evt) {
      evt.preventDefault();
      console.log(evt.target)
      const href = evt.target.getAttribute("href") != null ? evt.target.getAttribute("href") : "#about";
      const el = href ? document.querySelector(href) : null;
      const targetId = href.replace("#", "");
      const anchorTag = document.getElementById(targetId);
      const navlinks = document.getElementsByClassName("nav-link");
      const navItems = document.getElementsByClassName("nav-item");
      if (el) {
        // this.$refs.content.scrollTop = el.offsetTop;
        [...navlinks].forEach((element, index, array) => {
          const hrefLink = element.getAttribute("href").replace("#", "");
          if (hrefLink === targetId) { element.className += " active"; }
          else element.className = "nav-link";
        });
        [...navItems].forEach((element, index, array) => {
          element.className = "nav-item";
        });
        this.$scrollTo(el);
      }
    }
  }
};
</script>

<style scoped lang="scss">
.navbar-brand,
.nav-item {
  cursor: pointer;
}

#sideNav .navbar-nav .nav-item .nav-link {
  font-weight: 800;
  letter-spacing: 0.05rem;
  text-transform: uppercase;
}

#sideNav .navbar-toggler:focus {
  outline-color: #d48a6e;
}

@media (min-width: 992px) {
  #sideNav {
    text-align: center;
    position: fixed;
    top: 0;
    left: 0;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    width: 17rem;
    height: 100vh;
  }
  #sideNav .navbar-brand {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    margin: auto auto 0;
    padding: 0.5rem;
  }
  #sideNav .navbar-brand .img-profile {
    max-width: 10rem;
    max-height: 10rem;
    border: 0.5rem solid rgba(255, 255, 255, 0.2);
  }
  #sideNav .navbar-collapse {
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    -webkit-box-align: start;
    -ms-flex-align: start;
    align-items: flex-start;
    -webkit-box-flex: 0;
    -ms-flex-positive: 0;
    flex-grow: 0;
    width: 100%;
    margin-bottom: auto;
  }
  #sideNav .navbar-collapse .navbar-nav {
    -webkit-box-orient: vertical;
    -webkit-box-direction: normal;
    -ms-flex-direction: column;
    flex-direction: column;
    width: 100%;
  }
  #sideNav .navbar-collapse .navbar-nav .nav-item {
    display: block;
  }
  #sideNav .navbar-collapse .navbar-nav .nav-item .nav-link {
    display: block;
  }
}
</style>
