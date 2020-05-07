<template>
  <div class="Certificates col-sm-12 col-md-6">
    <h1>Certificates</h1>
    <hr />
    <div class="row">
      <div class="col-12">
        <img src="../assets/CTFL-new.jpg" alt="ISTQB Logo" id="istqb" />
        <h3>ISTQB Certified Tester Foundation Level</h3>
        <h5>Certified: December 2019</h5>
        <div class="text-left mt-3">
          <p>Topics covered:</p>
          <ul>
            <li>Fundamentals of Testing</li>
            <li>Testing through the SDLC</li>
            <li>Static Testing</li>
            <li>Test Techniques</li>
            <li>Test Management</li>
            <li>Tool Support for Testing</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "Certificates",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
#istqb {
  height: 15vh;
}

h3 {
  display: inline;
}

hr {
  border-color: black;
}
</style>