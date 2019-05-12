<template>
  <Layout>
    <div class="container-fluid p-0">
      <About/>
      <hr class="m-0">
      <Experience/>
      <hr class="m-0">
      <Education/>
      <hr class="m-0">
      <Skills/>
      <hr class="m-0">
      <Interests/>
      <hr class="m-0">
      <Awards/>
    </div>
  </Layout>
</template>

<script>
import About from "../components/About";
import Experience from "../components/Experience";
import Education from "../components/Education";
import Skills from "../components/Skills";
import Interests from "../components/Interests";
import Awards from "../components/Awards";

export default {
  components: {
    About,
    Experience,
    Education,
    Skills,
    Interests,
    Awards
  },
  metaInfo: {
    title: "Gridsome starter bootstrap"
  }
};
</script>

<style>
.subheading {
  text-transform: uppercase;
  font-weight: 500;
  font-family: "Saira Extra Condensed", -apple-system, BlinkMacSystemFont,
    "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif, "Apple Color Emoji",
    "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";
  font-size: 1.5rem;
}

.fa-ul > li {
  display: flex;
  align-items: center;
}

.social-icons a {
  display: inline-block;
  height: 3.5rem;
  width: 3.5rem;
  background-color: #495057;
  color: #fff !important;
  border-radius: 100%;
  text-align: center;
  font-size: 1.5rem;
  line-height: 3.5rem;
  margin-right: 1rem;
  cursor: pointer;
}

.social-icons a:last-child {
  margin-right: 0;
}

.social-icons a:hover {
  background-color: #bd5d38;
}

.dev-icons {
  font-size: 3rem;
}

.dev-icons .list-inline-item svg:hover {
  color: #bd5d38;
}

section.resume-section {
  padding-top: 5rem !important;
  padding-bottom: 5rem !important;
  max-width: 75rem;
}

section.resume-section .resume-item .resume-date {
  min-width: none;
}

@media (min-width: 768px) {
  section.resume-section {
    min-height: 100vh;
  }
  section.resume-section .resume-item .resume-date {
    min-width: 18rem;
  }
}

@media (min-width: 992px) {
  section.resume-section {
    padding-top: 3rem !important;
    padding-bottom: 3rem !important;
  }
}

.bg-primary {
  background-color: #bd5d38 !important;
}

.text-primary {
  color: #bd5d38 !important;
}

a {
  color: #bd5d38;
}

a:hover,
a:focus,
a:active {
  color: #824027;
}
</style>
