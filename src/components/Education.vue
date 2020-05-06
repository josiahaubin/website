<template>
  <div class="Education col-sm-12 col-md-6">
    <h1>Education</h1>
    <hr />
    <!-- Boise CodeWorks -->
    <div class="row">
      <div class="col-12">
        <img src="../assets/cw-logo.png" alt="Boise CodeWorks Logo" id="bcw" />
        <h2 class="ml-3">Boise CodeWorks</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-12 mt-3">
        <h3>Junior Software Development Student</h3>
        <h5>Fall 2019 Cohort</h5>
      </div>
      <div class="col-12">
        <p
          class="text-left"
        >A Junior Software Development Student where I completed a 13 week immersive program, learning multiple front and back-end technologies, and completing various projects that met various requirements and strict deadlines.</p>
      </div>
    </div>
    <!-- Boise State -->
    <div class="row">
      <div class="col-12">
        <img src="../assets/B-Logo_500x.jpg" alt="Boise State Logo" id="bsu" />
        <h2>Boise State University</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-12 mt-3">
        <h3>BBA | Information Technology Management</h3>
        <h5>Spring 2019 | 3.994 GPA</h5>
      </div>
      <div class="col-12">Class details</div>
    </div>
  </div>
</template>


<script>
export default {
  name: "Education",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
#bcw {
  height: 15vh;
}

#bsu {
  height: 15vh;
}

hr {
  border-color: black;
}

h2 {
  display: inline;
}
</style>