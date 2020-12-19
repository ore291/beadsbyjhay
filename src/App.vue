<template>
  <div id="app">
    <NavBar />
    <Main />
    <Footer />
  </div>
</template>

<script>
import NavBar from './components/Nav'
import Main from './components/Main'
import Footer from './components/Footer'

export default {
  name: 'App',
  components: {
    NavBar,
    Main,
    Footer
  }
}
</script>

<style>

</style>
