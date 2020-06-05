<template>
  <div id="app">
    <Home/>
    <VuexplosiveModal :visible='showModal' :title='title' :content='content' :footer='footer' />
    <Footer/>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Footer from './components/Footer.vue'
import VuexplosiveModal from 'vuexplosive-modal'

export default {
  name: 'App',
  components: {
    Home,
    Footer,
    VuexplosiveModal
  },
  mounted () {
    setTimeout(() => {
      this.showModal = true
    }, 10000)
  },
  data () {
    return {
      showModal: false,
      title: '🔥 Stay Safe!',
      content: '<p>Check out our API for sending Emails in Apps if you are a developer. It is Absolutely free! Sorry for interruption. </p>',
      footer: '<a  target="_blank" href="https://sendmail.azuatech.co.ke">Click to go to Xend Mail API<a>'
    }
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
