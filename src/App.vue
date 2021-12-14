<template>
  <div id="app">
    <Header/>
    <Main/>
    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue'
import Main from './components/Main.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Main,
    Footer
  }
}
</script>

<style lang="scss">
@import '~@fortawesome/fontawesome-free/css/all.min.css';

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

// pulsanti
.button {
            color: white;
            background-color: #5eddcc;
            opacity: .7;
            width: 170px;
            margin-top: 35px;
            padding: 12px 18px;
            letter-spacing: 2px;
            border-radius: 18px;
            display: flex;
            justify-content: center;
            align-items: center;

            &:hover {
                opacity: 1;
                cursor: pointer;
            }
        }

</style>
