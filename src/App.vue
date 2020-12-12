<template>
  <div id="app">
    <div class="container">
    </div>
    <router-view />
  </div>
</template>

<script>
export default {
  name: "App",
  components: {},
};
</script>

<style>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@600;900&display=swap");
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  text-decoration: none;
  font-family: "Poppins", sans-serif;
}
html {
  background: linear-gradient(rgba(22, 22, 22, 0.76), rgba(22, 22, 22, 0.76)),
    url("./assets/Login_image.jpg");
  background-size: cover;
  background-attachment: fixed;
  background-position: center;
}
.container {
  margin: 3rem;
}
</style>
