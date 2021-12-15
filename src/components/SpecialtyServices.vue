<template>
    <section class="my-specialty-services">
        <!-- testo sopra -->
        <div class="text">
            <span>Specialty Services</span>
            <div class="line"></div>
            <p>
                Lorem ipsum, dolor sit amet consectetur adipisicing elit. Facere facilis labore alias sapiente voluptate iste accusantium aliquam dolorum.
            </p>
            <p>
                Beatae sequi veritatis laborum sed minima, rerum quod.
            </p>
        </div>

        <!-- servizi -->
        <div class="services">

            <div class="small-business-loans">
                <i class="fas fa-globe"></i>
                <span>Small Business Loans</span>
                <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Odio officia ea ipsam quis perferendis laborum.
                </p>
                <div class="btn-learn-more" >
                    Learn More
                </div>

            </div>

            <div class="credit-rating-advice">
                <i class="far fa-gem"></i>
                <span>Credit Rating Advice</span>
                <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Odio officia ea ipsam quis perferendis laborum.
                </p>
                <div class="btn-learn-more" >
                    Learn More
                </div>
            </div>

            <div class="fast-croud-funding">
                <i class="fas fa-chart-line"></i>
                <span>Fast Crowd Funding</span>
                <p>
                    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Odio officia ea ipsam quis perferendis laborum.
                </p>
                <div class="btn-learn-more" >
                    Learn More
                </div>
            </div>

        </div>


    </section>
</template>

<script>
export default {
  name: 'SpecialtyServices'

}
</script>


<style scoped lang="scss">
.my-specialty-services {
    background-color: #f6f7f7;
    padding: 100px 0;
}

.text {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 100px;

    span {
        font-size: 40px;
    }

    p {
        margin: 5px 0;
    }
}

.services {
    display: flex;
    justify-content: center;
    align-items: center;

    & > div {
        width: 300px;
        height: 340px;
        margin: 0px 10px;
        padding: 25px 20px;
        background-color: white;
        display: flex;
        flex-direction: column;
        align-items: center;
        position: relative;

        span {
            font-size: 25px;
            margin: 15px 0;
            transition: all .5s ease-in;      

        }

        p {
            text-align: center;
            line-height: 23px;
        }

        i {
            font-size: 50px;
            color: #426ead;
            transition: all .5s ease-in;      

        }

        .btn-learn-more {
            color: white;
            background-color: #5eddcc;
            text-align: center;
            padding: 7px 0px;
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            transition: all .5s ease-in;      
        }

        &:hover {
            cursor: pointer;
        }

        &:hover span,
        &:hover i {
            color: #5eddcc;
        }
        &:hover .btn-learn-more {
            background-image: linear-gradient(to top, #0acfdb,  #5eddcc);
        }


    }
}
</style>
