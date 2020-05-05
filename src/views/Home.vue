<template>
  <div class="home">
    <div class="row">
      <ContactMe />
      <AboutMe />
    </div>
    <div class="row">
      <Experience />
      <Education />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import ContactMe from "../components/ContactMe.vue";
import AboutMe from "../components/AboutMe.vue";
import Education from "../components/Education.vue";
import Experience from "../components/Experience.vue";

export default {
  name: "Home",
  components: {
    ContactMe,
    AboutMe,
    Experience,
    Education
  }
};
</script>