<template>
  <div class="ContactMe col-sm-12 col-md-4">
    <div class="mt-3">
      <div class="card p-3">
        <h2>Contact Me</h2>
        <ul class="text-left ml-2">
          <li>
            Email:
            <b>josiahaubin@gmail.com</b>
          </li>
          <li>
            LinkedIn:
            <a href="https://www.linkedin.com/in/josiah-aubin/">Josiah Aubin</a>
          </li>
          <li>
            Github:
            <a href="https://github.com/josiahaubin">josiahaubin</a>
          </li>
        </ul>
      </div>
    </div>
    <img src="../assets/codeworks.jpg" alt="Josiah's CodeWorks class" class="mt-4 rounded" />
    <small>CodeWorks instructors, classmates, and myself on graduation day</small>
  </div>
</template>


<script>
export default {
  name: "ContactMe",
  data() {
    return {};
  },
  computed: {},
  methods: {},
  components: {}
};
</script>


<style scoped>
img {
  width: inherit;
  height: 50vh;
}
li {
  list-style-type: none;
  font-size: 20px;
}
.card {
  border-color: black;
  box-shadow: 2px 2px 0px lightgray;
}
</style>