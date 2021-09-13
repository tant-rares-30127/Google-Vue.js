<template>
  <Header></Header>
  <UpSpacer></UpSpacer>
  <MainContent></MainContent>
  <DownSpacer></DownSpacer>
  <UpperFooter></UpperFooter>
  <LowerFooter></Lowerfooter>
</template>

<script>
import Header from './components/Header.vue'
import UpSpacer from './components/UpSpacer.vue'
import MainContent from './components/MainContent.vue'
import DownSpacer from './components/DownSpacer.vue'
import UpperFooter from './components/UpperFooter.vue'
import LowerFooter from './components/LowerFooter.vue'

export default {
  name: 'App',
  components: {
    Header,
    UpSpacer,
    MainContent,
    DownSpacer,
    UpperFooter,
    LowerFooter
  }

    }
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
