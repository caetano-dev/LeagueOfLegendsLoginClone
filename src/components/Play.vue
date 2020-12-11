<template>
  <div class="Main">
    <div class="ImageContainer">
      <img
        class="Exclamation"
        src="../assets/exclamation.svg"
        alt="Exclamation"
      />
    </div>
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
.Exclamation {
  width: 3rem;
  margin-left: -0.3rem;
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
  letter-spacing: -1rem;
}
h1:hover {
  color: #1dcdda;
}
.PlayIcon {
  height: 15rem;
  padding-left: 1rem;
}
</style>
