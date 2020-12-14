<template>
  <div class="Main">
    <div class="TextContainer">
      <div class="MainText">
        <router-link tag="h1" class="Play" to="/login">PLAY</router-link>
      </div>
      <img class="PlayIcon" src="../assets/play.png" alt="PlayIcon" />
    </div>
  </div>
</template>

<script>
export default {
  name: "Play",
};
</script>

<style scoped>
.Main {
  padding-top: 4rem;
}
.TextContainer {
  display: flex;
  justify-content: center;
  align-items: center;
  width: 100%;
}
.MainText {
  display: flex;
  justify-content: center;
  text-align: center;
}
.Play {
  font-size: 10rem;
  color: white;
  letter-spacing: -0.4rem;
  cursor: pointer;
}
.Play:hover {
  color: #1dcdda;
}
.PlayIcon {
  height: 7.5rem;
  padding-left: 1rem;
  cursor: pointer;
}
</style>
