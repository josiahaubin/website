<template>
  <div id="app" class="container-fluid">
    <div id="nav">
      <div class="row">
        <div class="col-sm-12 col-md-4">
          <img
            src="./assets/Josiah Aubin 113145170(1) - Copy.jpg"
            alt="Josiah Profile Picture"
            id="josiahphoto"
            class="circle"
          />
        </div>
        <div class="col-sm-12 col-md-8 text-white mt-5">
          <div id="name">
            <h1>
              Josiah Aubin
              <br />Software Developer
            </h1>
          </div>
        </div>
      </div>
      <div id="links" class="row mx-auto mt-2">
        <div class="col-12">
          <router-link to="/" class="mr-2">Home</router-link>||
          <router-link to="/about">Resume</router-link>
        </div>
      </div>
    </div>
    <router-view />
  </div>
</template>

<style>
#app {
  font-family: "Inconsolata", monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#links {
  background-color: rgb(250, 250, 250, 0.9);
  width: fit-content;
}

#links a {
  font-size: 19px;
}

#josiahphoto {
  width: auto;
  height: 40vh;
  border-radius: 25px;
}

#name {
  background-color: rgb(0, 0, 0, 0.7);
  width: fit-content;
}

#name h1 {
  font-size: 75px;
}

#nav {
  padding: 30px;
  background-image: url("./assets/markus-spiske-qjnAnF0jIGk-unsplash.jpg");
  background-size: cover;
  background-position-y: center;
  height: auto;
  margin-left: -15px;
  margin-right: -15px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}

::-webkit-scrollbar {
  display: none;
}
</style>
