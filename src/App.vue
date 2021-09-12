<template>
  <div>
    <Header />
    <router-view></router-view>
    <Footer />
  </div>
</template>
<style>
@import url('/css/style.css');
@import url('https://fonts.googleapis.com/css2?family=Nunito&display=swap');

#app {
  font-family: 'Nunito';
}

</style>

<script>
import Header from './components/layout/Header.vue'
import Footer from './components/layout/Footer.vue'

export default {
  components: {
    Header,
    Footer
  }
}
</script>