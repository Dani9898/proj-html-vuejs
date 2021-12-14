<template>
    <section class="my-cloud-based-finance">
        <!-- testo sinistra -->
        <div class="col-sx">
            <span>Cloud Based Finance</span>
            <div class="line"></div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est expedita, sit, error eaque laborum minus ex possimus eum eveniet nemo beatae.</p>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dignissimos velit molestiae, odit natus cupiditate sint unde autem aut ipsa consectetur, dolorum nesciunt enim sed atque esse placeat facere officia animi.</p>
            <div class="button">LEARN MORE</div>
        </div>
        <!-- img destra -->
        <div class="col-dx">
            <img src="../assets/img/graph-800x610.jpg" alt="graph">
        </div>
    </section>
</template>

<script>
export default {
  name: 'CloudBasedFinance'
}
</script>


<style scoped lang="scss">
.my-cloud-based-finance {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 120px 0;
    width: 80%;
    margin: auto;

    .col-sx {
        span {
            font-size: 40px;
        }

        .line {
            height: 2px;
            width: 70px;
            margin: 20px 0;
            background-color: #1b304b;
        }

        p {
            margin: 13px 0;
            width: 85%;
            line-height: 22px;
        }
    }

    .col-dx {
        img {
            width: 650px;
        };
    }

}
</style>
