<template>
  <div id="app">
    <MainHeader/>
    <MainContent/>
    <HomeFooter/>
  </div>
</template>

<script>
import MainHeader from './components/Header.vue'
import MainContent from './components/Main.vue'
import HomeFooter from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    
    MainHeader,
    MainContent,
    HomeFooter
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
}
*{
  margin: 0%;
  padding: 0%;
  box-sizing: border-box;
}
ul{
  list-style: none;
}
a{
  color: currentColor;
  text-decoration: none;
}
</style>
