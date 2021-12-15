<template>
    <header>
      <!-- logo -->
      <img src="../assets/img/finance_logo_1x.png" alt="">

      <!-- menu -->
      <ul>
        <li :class="voce.active ? 'active' :  '' " v-for="voce, i in headerVociMenu" :key="i" ><a :class="voce.button ? 'button' : '' " href="#">{{voce.text}}</a></li>
      </ul>
    </header>
</template>

<script>
export default {
  name: 'Header',

  props: {
    headerVociMenu: Array
  },

  data() {
    return {
    }
  }

}
</script>


<style scoped lang="scss">
header {
  height: 90px;
  display: flex;
  align-items: center;
  justify-content: space-around;

  ul {
    display: flex;
    align-items: center;
    list-style-type: none;
    
    li {

      a {
        color: #949494;
        text-decoration: none;
        padding: 42px 25px;
        transition: all .3s linear;
        &.button {
          width: 120px;
          margin: 0;
          color:#fff;
          padding: 12px 0;
        }
      }

      &.active a {
        background-color: #f6f7f7;
        color: #1b304b;
      }

      &:hover a:not(.button){
        background-color: #f6f7f7;
      }
    }
  }

}
</style>
