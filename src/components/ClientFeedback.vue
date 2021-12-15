<template>
    <section class="my-client-feedback">
        <!-- titolo -->
        <div class="title">
            <span>Client Feedback</span>
            <div class="line"></div>
        </div>
        <!-- clients -->
        <div class="clients">
            <div class="client" v-for="client, i in clients" :key="i">
                <div class="feedback">
                    <img :src="require(`../assets/img/${client.img}`)" alt="logo company">
                    <p>
                        "Avada Finance offers a fantastic service! It is so easy to use and the customer support is the best around. This payment option is my number one choice. I always recommend it".
                    </p>
                </div>
                <div class="author">
                    <h4>{{client.author}}</h4>
                    <span>{{client.company}}</span>
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
  name: 'ClientFeedback',

  data(){
      return{
          clients: [
              {
                  img: "client-logo-4.png",
                  text: "'Avada Finance offers a fantastic service! It is so easy to use and the customer support is the best around. This payment option is my number one choice. I always recommend it'.",
                  author: "ANDRE MENDOZA",
                  company: "CREATIVE MARKET"
              },
              {
                  img: "client-logo-1-1.png",
                  text: "'Avada Finance offers a fantastic service! It is so easy to use and the customer support is the best around. This payment option is my number one choice. I always recommend it'.",
                  author: "ANDRE MENDOZA",
                  company: "CREATIVE MARKET"
              },
              {
                  img: "client-logo-2.png",
                  text: "'Avada Finance offers a fantastic service! It is so easy to use and the customer support is the best around. This payment option is my number one choice. I always recommend it'.",
                  author: "ANDRE MENDOZA",
                  company: "CREATIVE MARKET"
              },
              {
                  img: "client-logo-3.png",
                  text: "'Avada Finance offers a fantastic service! It is so easy to use and the customer support is the best around. This payment option is my number one choice. I always recommend it'.",
                  author: "ANDRE MENDOZA",
                  company: "CREATIVE MARKET"
              }
          ]
      }
  }
}
</script>


<style scoped lang="scss">
.title {
    display: flex;
    flex-direction: column;
    align-items: center;
    font-size: 40px;
    background-color: #f6f7f7;
    padding: 80px;
}

.clients {
    display: flex;

    .client {
        width: 25%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        border: 1px solid #ebebeb;
        border-left: none;

        .feedback {
            margin-bottom: 50px;
            display: flex;
            flex-direction: column;
            align-items: center;
            p {
                color: #949494;
                padding: 0 50px;
                font-size: 19px;
                text-align: center;
            }
        }

        .author {
            border-top: 1px solid #ebebeb;
            width: 100%;
            padding: 14px 0;
            text-align: center;

            span {
                font-size: 13px;
                color: #949494;
            }
        }
    }
}
</style>
