<template>
  <div class="Sidebar">
    <div class="ImageContainer">
      <img class="Logo" src="../assets/logo.png" alt="League of Legends logo" />
    </div>
    <div class="InputContainer">
      <div class="LoginText">
        <p>Fazer login</p>
      </div>
      <input placeholder="NOME DE USUÁRIO" />
      <input placeholder="SENHA" />
    </div>
    <div class="SocialMedia">
      <div class="FacebookContainer">
        <img class="social" src="../assets/facebook.png" alt="Facebook" />
      </div>
      <div class="GoogleContainer">
        <img class="social" src="../assets/google.png" alt="Google" />
      </div>
      <div class="AppleContainer">
        <img class="social" src="../assets/apple.png" alt="Apple" />
      </div>
    </div>
    <div class="checkbox">
      <input type="checkbox" />
      <span>Manter login</span>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sidebar",
};
</script>

<style scoped>
input {
  height: 2.3rem;
  background-color: rgb(240, 240, 240);
  margin: 1.3rem 0rem -0.3rem 0rem;
  padding: 0.4rem;
  border: none;
  outline: none;
  border-radius: 0.2rem;
  transition: 0.1s;
}
input:focus {
  border: 0.1rem solid rgb(59, 59, 59);
  background-color: rgb(255, 255, 255);
}
input:hover {
  background-color: rgb(235, 235, 235);
}
p {
  font-size: 1.1rem;
  letter-spacing: -1px;
}
.social {
  width: 1rem;
  border: 1px solid red;
}
.Sidebar {
  padding: 3.2rem 3rem 12.7rem 3rem;
  background-color: white;
  margin-right: 44.7rem;
}
.Logo {
  width: 2rem;
}
.ImageContainer {
  display: flex;
  justify-content: center;
  padding-bottom: 2.5rem;
}
.LoginText {
  display: flex;
  justify-content: center;
}
.InputContainer {
  display: flex;
  flex-direction: column;
  justify-content: center;
}
.SocialMedia {
  margin-top: 2rem;
  display: flex;
  justify-content: space-between;
}

</style>
