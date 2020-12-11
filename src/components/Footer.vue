<template>
  <div class="Main">
    <div class="LogoContainer">
      <div class="LogoGroup">
      <img class="Riot" src="../assets/riot.png" alt="Riot logo">
      <img class="Lol" src="../assets/lol.png" alt="Logo">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Footer",
};
</script>

<style scoped>
.LogoContainer{
  margin-top: 2rem;
}
.LogoGroup{
  display: flex;
  align-items: center;
}
.Lol{
  width: 15rem;
  border-left: 0.1rem solid #b4b4b4be;
  
}
.Riot{
  width: 5rem;
  margin-right: 0.5rem
}

</style>
