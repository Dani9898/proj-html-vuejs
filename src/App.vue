<template>
  <div id="app">
    <Header :headerVociMenu="headerMenu" />
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
  },

  data(){
    return {
      headerMenu: [
        {
          text: "HOME",
          active: true,
          button: false

        },
        {
          text: "ABOUT",
          active: false,
          button: false
        },
        {
          text: "SERVICES",
          active: false,
          button: false
        },
        {
          text: "PACKAGES",
          active: false,
          button: false
        },
        {
          text: "INSIGHT",
          active: false,
          button: false
        },
        {
          text: "CONTACT",
          active: false,
          button: true
        },
        {
          text: "+",
          active: false,
          button: false
        }
      ]
    }
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
  border-radius: 20px;
  display: flex;
  justify-content: center;
  align-items: center;
  transition: all .3s linear;

  &:hover {
      opacity: 1;
      cursor: pointer;
  }
}

.line {
  height: 2px;
  width: 70px;
  margin: 20px 0;
  background-color: #1b304b;
}


</style>
