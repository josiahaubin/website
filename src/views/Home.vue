<template>
  <div class="home">
    <div class="row">
      <ContactMe />
      <AboutMe />
    </div>
    <div class="row mt-3">
      <Experience />
      <Education />
    </div>
    <div class="row mt-3">
      <Certificates />
      <HonorsAwards />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import ContactMe from "../components/ContactMe.vue";
import AboutMe from "../components/AboutMe.vue";
import Education from "../components/Education.vue";
import Experience from "../components/Experience.vue";
import Certificates from "../components/Certificates.vue";
import HonorsAwards from "../components/HonorsAwards.vue";

export default {
  name: "Home",
  components: {
    ContactMe,
    AboutMe,
    Experience,
    Education,
    Certificates,
    HonorsAwards
  }
};
</script>