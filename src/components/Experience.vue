<template>
  <div class="Experience col-sm-12 col-md-6">
    <h1>Experience</h1>
    <hr />
    <!-- In Time Tec -->
    <div class="row">
      <div class="col-12">
        <img
          src="../assets/49896370_2076027085806843_1352515042943172608_n.png"
          alt="InTimeTec Logo"
          id="intimetec"
        />
        <h2 class="ml-3">In Time Tec</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-6">
        <h3>Software Developer</h3>
        <h5>Nov. 2019 - Present</h5>
      </div>
      <div class="col-6">
        <p>Job details</p>
      </div>
    </div>
    <!-- ISP -->
    <div class="row mt-5">
      <div class="col-12">
        <img src="../assets/58f274437553b.image.jpg" alt="ISP Logo" id="isp" />
        <h2 class="ml-3">Idaho State Police</h2>
      </div>
    </div>
    <div class="row">
      <div class="col-6">
        <h3>Information Technology Intern</h3>
        <h5>Jan. 2019 - May 2019</h5>
      </div>
      <div class="col-6">
        <p>Job details</p>
      </div>
    </div>
  </div>
</template>


<script>
export default {
  name: "Experience",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
#intimetec {
  height: 15vh;
}

#isp {
  height: 15vh;
}

h2 {
  display: inline;
}

hr {
  border-color: black;
}
</style>