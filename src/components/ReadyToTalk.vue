<template>
    <section class="my-rtc">
        <div class="content">
            <span class="title">Ready to talk?</span>
            <p class="text">
                Lorem ipsum dolor sit amet, consectetur adipisicing elit. Sed aliquam ut porro consequuntur quo facere neque, error, minus blanditiis.
            </p>
            <div class="button">LET'S TALK</div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'ReadyToTalk'
}
</script>


<style scoped lang="scss">
.my-rtc {
    background-image: url("../assets/img/ready_to_talk_cta_bg.jpg");
    height: 500px;
    background-position: center;
    display: flex;
    justify-content: center;
    align-items: center;

    .content {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        height: 100%;
        width: 600px;
        text-align: center;

        .title {
            color: #fff;
            font-size: 53px;
            margin-bottom: 20px;        
        }

        .text {
            color: #949494;
            line-height: 30px;
        }

    }
}
</style>
