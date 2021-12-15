<template>
    <footer>
      <!-- sezione sopra -->
      <section class="top">
        <div class="content">
          <div class="logo">
            <img src="../assets/img/finance_logo_footer-200x131.png" alt="logo">
          </div>

          <!-- menu sx -->
          <nav class="sx">
            <div class="title">RECENT POSTS</div>

            <ul>
              <li v-for="voci, i in footerVociMenuSx" :key="i"><a :href="voci.link">{{voci.text}}</a></li>
            </ul>
          </nav>

          <!-- menu dx -->
          <nav class="center">
            <div class="title">SERVICES</div>

            <ul>
              <li v-for="voci, i in footerVociMenuCenter" :key="i"><a :href="voci.link">{{voci.text}}</a></li>
            </ul>
          </nav>

          <!-- latest -->
          <nav class="dx">
            <div class="title">LATEST</div>

            <ul>
              <li v-for="voci, i in footerVociMenuDx" :key="i"><a :href="voci.link"><i :class="'fab fa-' + voci.icon"></i></a></li>
            </ul>
            
          </nav>
        </div>
        <!-- logo -->
        
      </section>

      <!-- sezione sotto -->
      <section class="down">
        <div class="content">
          <span>
            &copy; Copyright 2012-2020 | Avada Theme by Them Fusion | All Rights Reserved |  Powered by WordPress
          </span>

          <div class="icons">

            <div class="circle"><i class="fab fa-facebook-f"></i></div>
            <div class="circle"><i class="fab fa-twitter"></i></div>
            <div class="circle"><i class="fab fa-youtube"></i></div>
            <div class="circle"><i class="fab fa-instagram"></i></div>

          </div>
        </div>
      </section>
    </footer>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    footerVociMenuSx: Array,
    footerVociMenuCenter: Array,
    footerVociMenuDx: Array
  }

}
</script>


<style scoped lang="scss">
  .top {
    background-color:#1c1b21;
    
    .content {
      padding: 50px 0;
      display: flex;
    }
    .logo {
      width: 25%;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    nav {
      width: 25%;
      margin-top: 25px;
      

      .title {
        color: #fff;
      }

      ul {
        list-style-type: none;

          li {
            margin: 25px 0;

            &:hover a {
              color: #5eddcc;
            }
          }
        
          a {
            color: #949494;
            text-decoration: none;
            transition: all .3s ease-in-out .1s;
          }

          i {
            color: #00ddff;
          }
      }
    }     
  }

  .down {
    background-color: #19191f;
      
      .content {
        padding: 35px 50px;
        display: flex;
        justify-content: space-between;
        align-items: center;

        span {
          color: #949494;
          font-size: 12px;
        }

        .icons {
          display: flex;

          .circle {
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #5eddcc;
            color: #fff;
            border-radius: 50%;
            padding: 9px 12px;
            margin: 0 5px;
            transition: all .3s ease-in-out .1s;

            &:hover {
              color: #949494;
              background-color: #f6f7f7;
              cursor: pointer;
            }
          }
        }
      }
      
  }
</style>
