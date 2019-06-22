<template>
  <Layout>
    <div>
      <About/>
      <hr>
      <Experience/>
      <hr>
      <Skills/>
      <hr>
      <Training/>
      <hr>
      <Education/>
      <hr>
      <Interests/>
    </div>
  </Layout>
</template>

<script>
import About from "../components/About";
import Experience from "../components/Experience";
import Skills from "../components/Skills";
import Training from "../components/Training";
import Education from "../components/Education";
import Interests from "../components/Interests";
export default {
  components: {
    About,
    Experience,
    Skills,
    Training,
    Education,
    Interests
  },
  metaInfo: {
    title: "Ruby Resume",
  }
};
</script>

<style lang="scss">
.subheading {
  text-transform: uppercase;
  font-weight: 500;
  @include heading-font;
  font-size: 1.5rem;
}
.fa-ul > li {
  display: flex;
  align-items: center;
}
.dev-icons {
  font-size: 3rem;
}
.dev-icons .list-inline-item svg:hover {
  color: var(--primary);
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
</style>