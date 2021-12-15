<template>
    <section class="my-inv-numbers">
        <!-- learn more - img -->
        <div class="col-sx">
            <div class="content">
                <div>Investement Numbers</div>
                <div class="title">Making An Impact In Our Communities</div>
                <div class="button">Learn More</div>
            </div>
        </div>
        <!-- numbers -->
        <div class="col-dx">
            
            <div class="content">
                <div class="stats">
                    <span class="number">86%</span>
                    <span class="field">Successful Applications</span>
                </div>
                <div class="stats">
                    <span class="number">94%</span>
                    <span class="field">Return On Investment</span>
                </div>
                <div class="stats">
                    <span class="number">92%</span>
                    <span class="field">Applied Solutions</span>
                </div>
                <div class="stats">
                    <span class="number">100%</span>
                    <span class="field">Completely Secure</span>
                </div>
            </div>

        </div>
    </section>
</template>

<script>
export default {
  name: 'InvestmentsNumbers'
}
</script>


<style scoped lang="scss">
    .my-inv-numbers {
        display: flex;
    }

    .col-sx {
        height: 500px;
        width: 30vw;
        background-image: url("../assets/img/counters-bg-image.jpg");
        background-size: cover;
        background-repeat: no-repeat;
        color: white;

        .content {
            display: flex;
            flex-direction: column;
            justify-content: center;
            height: 100%;
            margin: 0 90px;

                
            .title {
                font-size: 40px;
                margin-top: 22px;
            }

            .button {
                width: 130px;
                padding: 8px 16px;
            }
        }


    }
    .col-dx {
        width: 70vw;
        display: flex;
        justify-content: center;
        align-items: center;
        
        .content {
            width: 80%;
            display: flex;
            flex-wrap: wrap;

            .stats {
                width: 50%;
                margin: 45px auto;
                display: flex;
                flex-direction: column;
                align-items: center;

                .number {
                    color: #426ead;
                    font-size: 55px;
                }

                .field {
                    color: #949494;
                }
            }
        }
        
    }
</style>
