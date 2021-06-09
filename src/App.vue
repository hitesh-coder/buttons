<template>
  <div id="buttons">
    <div class="h2">Buttons</div>
    <Buttons />
    <footer>Created by
      <a href="https://github.com/hitesh-coder">HITESH</a> - devChallenges.io
    </footer>
    <link
      href="https://fonts.googleapis.com/css2?family=Noto+Sans+JP:wght@500&family=Poppins:wght@500&family=Ubuntu+Mono&display=swap"
      rel="stylesheet"
    />
  </div>
</template>

<script>
import Buttons from "./components/Buttons.vue";

export default {
  name: "App",
  components: {
    Buttons,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/bootstrap.scss";

* {
  font-family: "Noto Sans JP", sans-serif;
  white-space: nowrap;
}

#buttons {
  padding: 5em 20vw;
}

.h2 {
  font-family: Poppins;
  font-style: normal;
  // font-weight: 500;
  // font-size: 24px;
  // line-height: 36px;
  /* identical to box height */

  /* Gray 2 */

  color: #4f4f4f;
  margin-bottom: 2rem;
}

.h6 {
  font-family: Ubuntu Mono;
}

footer{
    height: 5vh;
    font-family: Montserrat;
    font-style: normal;
    font-weight: 500;
    font-size: 14px;
    line-height: 17px;
    margin-top: 100px;

    text-align: center;

    color: #BDBDBD;

    a{
        font-weight: 700;
        color: #a1a1a1;
    }
}

@media screen and (max-width:$modal-lg) {
  #buttons{
    padding: 3em 5vw;
  }
}
</style>
