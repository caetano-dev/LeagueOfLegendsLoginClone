<template>
  <div class="Main">
    <div class="TextContainer">
      <div class="MainText">
        <h1 class="Play">PLAY</h1>
      </div>
      <img class="PlayIcon" src="../assets/play.svg" alt="PlayIcon" />
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
  display: flex;
  padding-top: 0.5rem;
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
  font-size: 18rem;
  color: white;
  letter-spacing: -0.4rem;
}
h1:hover {
  color: #1dcdda;
}
.PlayIcon {
  height: 15rem;
  padding-left: 1rem;
}
</style>
