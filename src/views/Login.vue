<template>
  <div class="Container">
    <Sidebar />
  </div>
</template>

<script>
import Sidebar from "../components/Sidebar";
export default {
  name: "App",
  components: {
    Sidebar,
  },
};
</script>

<style scoped>
@import url("https://fonts.googleapis.com/css2?family=Poppins:wght@600;900&display=swap");
* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
  text-decoration: none;
  font-family: "Poppins", sans-serif;
}
.Container {
  background: linear-gradient(rgba(61, 82, 81, 0.137), rgba(61, 82, 81, 0.137)),
    url("../assets/Login_image.jpg");
  background-size: cover;
  background-attachment: fixed;
  background-position: center;
}
</style>
