<template>
  <div id="app">
    <Header></Header>
    <MovieSlide></MovieSlide>
    <MovieChart></MovieChart>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import MovieSlide from './components/MovieSlide.vue'
import MovieChart from './components/MovieChart.vue'
import Footer from './components/Footer.vue'

export default {
  components : {
    'Header' : Header,
    'MovieSlide' : MovieSlide,
    'MovieChart' : MovieChart,
    'Footer' : Footer
  }
}
</script>

<style>

</style>