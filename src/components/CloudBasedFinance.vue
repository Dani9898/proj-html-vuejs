<template>
    <div class="my-cloud-based-finance">
        <div class="col-sx">
            <span>Cloud Based Finance</span>
            <div class="line"></div>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Est expedita, sit, error eaque laborum minus ex possimus eum eveniet nemo beatae.</p>
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dignissimos velit molestiae, odit natus cupiditate sint unde autem aut ipsa consectetur, dolorum nesciunt enim sed atque esse placeat facere officia animi.</p>
            <div class="button">LEARN MORE</div>
        </div>
        <div class="col-dx">
            <img src="../assets/img/graph-800x610.jpg" alt="graph">
        </div>
    </div>
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
            background-color: black;
        }

        p {
            margin: 13px 0;
            width: 85%;
            line-height: 22px;
        }

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
    }

    .col-dx {
        img {
            width: 650px;
        };
    }

}
</style>
