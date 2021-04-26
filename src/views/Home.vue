<template>
  <div class="home">
    <Header/>
    <MainPage msg="Welcome to Your Vue.js App"/>
    <Footer/>
  </div>
</template>

<script>
// @ is an alias to /src
import MainPage from '@/components/MainPage.vue'
import Header from '@/components/Header.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    MainPage,
    Header,
    Footer
  }
}
</script>
