<template>
  <div class="home">
    <div class="row">
      <ContactMe />
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import ContactMe from "../components/ContactMe.vue";
export default {
  name: "Home",
  components: {
    ContactMe
  }
};
</script>
