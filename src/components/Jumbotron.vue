<template>
    <div id="myjumbotron">
      <h1>Right People. Right Investments<span class="dot">.</span></h1>
    </div>
</template>

<script>
export default {
  name: 'Jumbotron'

}
</script>


<style scoped lang="scss">
#myjumbotron {
    height: calc(100vh - 100px);
    background-image: url("../assets/img/home_finance_slider_bg.jpg");
    background-size: contain;
    position: relative;

      h1{
        width: 100%;
        text-align: center;
        color: white;
        font-size: 55px;
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
      }
      
      .dot {
        color: #5ddecc;
      }
}
</style>
