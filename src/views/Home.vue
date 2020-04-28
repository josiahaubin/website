<template>
  <div class="home">
    <div class="row">
      <ContactMe />
      <AboutMe />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import ContactMe from "../components/ContactMe.vue";
import AboutMe from "../components/AboutMe.vue";
export default {
  name: "Home",
  components: {
    ContactMe,
    AboutMe
  }
};
</script>
