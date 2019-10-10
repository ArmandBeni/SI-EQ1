<template>
  <div id="app">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Main from './views/Main'
import Header from './components/Header'
import Footer from './components/Footer'

export default {
  name: 'app',
  components: {
    Main,
    Header,
    Footer
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css?family=Be+Vietnam&display=swap');

html, body{
  margin: 0;
  font-family: 'Be Vietnam', sans-serif;
}

#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  font-family: 'Be Vietnam', sans-serif;
}
</style>
