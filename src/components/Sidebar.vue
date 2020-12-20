<template>
  <div class="Sidebar">
    <div class="ImageContainer">
      <img class="Logo" src="../assets/logo.png" alt="League of Legends logo" />
    </div>
    <div class="InputContainer">
      <div class="LoginText">
        <p>Sign in</p>
      </div>
      <input placeholder="USERNAME" />
      <input type="password" v-model="characters" placeholder="PASSWORD" />
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
      <span>Stay signed in</span>
    </div>
    <div class="ButtonContainer">
      <div class="Button">
        <img
          :class="{ RedButton: characters.length > 3 }"
          class="Arrow"
          src="../assets/arrow.svg"
          alt="Next"
        />
      </div>
      <div class="ButtonText">
        <p>CAN'T SIGN IN?</p>
        <p>CREATE ACCOUNT</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Sidebar",
  data() {
    return {
      characters: "",
    };
  },
};
</script>

<style scoped>
input {
  height: 2.3rem;
  background-color: rgb(240, 240, 240);
  margin: 1.3rem 0rem -0.1rem 0rem;
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
input::placeholder {
  font-size: 0.55rem;
  font-weight: 700;
  color: rgb(179, 179, 179);
}
input:hover {
  background-color: rgb(235, 235, 235);
}
p {
  font-size: 1.1rem;
  letter-spacing: -1px;
}
.Sidebar {
  padding: 3.4rem 3rem 2.35rem 3rem;
  background-color: rgb(247, 247, 247);
  margin-right: 44.7rem;
}
.Logo {
  width: 2rem;
}
.LoginText,
.ImageContainer,
.InputContainer,
.FacebookContainer,
.GoogleContainer,
.AppleContainer,
.Button {
  display: flex;
  justify-content: center;
}
.ImageContainer {
  padding-bottom: 2.5rem;
}
.InputContainer {
  flex-direction: column;
}
.SocialMedia {
  margin-top: 1.5rem;
  height: 1.6rem;
  display: flex;
  justify-content: space-between;
}
.SocialMedia > div {
  padding: 0.4rem 1rem 0rem 1rem;
}
.social {
  width: 0.9rem;
  padding-bottom: 0.3rem;
}
.FacebookContainer,
.GoogleContainer,
.AppleContainer {
  align-items: center;
  width: 4.9rem;
  border-radius: 0.2rem;
  cursor: pointer;
}
.FacebookContainer {
  background-color: #387df5;
}
.FacebookContainer:hover {
  background: #316fd8;
}
.GoogleContainer {
  background-color: #ffffff;
  border: 1.5px solid rgb(245, 245, 245);
}
.GoogleContainer:hover {
  border: 1.5px solid rgb(233, 233, 233);
  background: rgb(248, 248, 248);
}
.AppleContainer {
  background-color: #000000;
}
.AppleContainer:hover {
  background: #111111;
}
.checkbox {
  display: flex;
  align-items: center;
  margin: -1.4rem 0rem 0rem 0rem;
}
span {
  font-size: 0.6rem;
  color: #979595;
  padding: 1.6rem 0rem 0rem 0.4rem;
}
.ButtonContainer {
  padding: 4.5rem 0rem 0rem 0rem;
  width: 100%;
}
.Arrow {
  border: 0.1rem solid #e6e6e6;
  border-radius: 1rem;
  width: 3rem;
  padding: 0.7rem;
  cursor: pointer;
}
.RedButton {
  background-color: rgb(230, 62, 62);
  border: rgb(230, 62, 62);
  cursor: pointer;
}
.Button {
  width: 100%;
  padding: 0rem 0rem 3.3rem 0rem;
}
.ButtonText {
  width: 100%;
  text-align: center;
}
.ButtonText p {
  font-size: 0.63rem;
  word-spacing: 0.1rem;
  color: #c4c4c4;
  cursor: pointer;
}
.ButtonText p:hover {
  color: #000000;
}
</style>
