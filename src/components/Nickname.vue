<template>
  <div class="HeaderContainer">
    <div class="NickNameContainer">
      <h3 class="NickName">Drull</h3>
      <span class="Tag">#BR1</span>
    </div>
    <p class="Session">SIGN OUT</p>
  </div>
</template>

<script>
export default {
  name: "Nickname",
};
</script>

<style scoped>
.NickNameContainer {
  display: flex;
}
.NickName {
  color: rgb(255, 255, 255);
  font-size: 1rem;
  font-weight: normal;
}
.Tag {
  padding-left: 0.3rem;
  color: #aaaaaa;
}
.Session {
  font-size: 0.57rem;
  color: rgb(64, 207, 233);
  letter-spacing: -0.4px;
}
</style>
