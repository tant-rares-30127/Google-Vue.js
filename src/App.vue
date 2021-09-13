<template>
  <div class="allpage">
    <Header></Header>
    <UpSpacer></UpSpacer>
    <MainContent></MainContent>
    <DownSpacer></DownSpacer>
    <UpperFooter></UpperFooter>
    <LowerFooter></LowerFooter>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import UpSpacer from "./components/UpSpacer.vue";
import MainContent from "./components/MainContent.vue";
import DownSpacer from "./components/DownSpacer.vue";
import UpperFooter from "./components/UpperFooter.vue";
import LowerFooter from "./components/LowerFooter.vue";

export default {
  name: "App",
  components: {
    Header,
    UpSpacer,
    MainContent,
    DownSpacer,
    UpperFooter,
    LowerFooter,
  },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

html {
  height: 100%;
  min-height: 100%;
}

.allpage {
  height: 100vh;
  display: flex;
  flex-direction: column;
}

a {
  margin: 10px 10px;
  align-self: center;
}

.up-spacer {
  flex-grow: 0.3;
}

.down-spacer {
  flex-grow: 1;
}

.textLink {
  text-decoration: none;
  color: black;
  color: rgba(0, 0, 0, 0.54);
}

.textLink:hover {
  text-decoration: underline;
}

@media (max-width: 800px) {
  .hero .form-container form input {
    width: 500px;
  }
  .lowerfooter {
    flex-direction: column;
  }
}
</style>
