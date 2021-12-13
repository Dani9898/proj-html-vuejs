<template>
    <main>
        <Jumbotron/>
        <Clients/>
    </main>
</template>

<script>
import Jumbotron from './Jumbotron.vue'
import Clients from './Clients.vue'


export default {
  components: { 
    Jumbotron,
    Clients
  },
  
  name: 'Main'

}
</script>


<style scoped lang="scss">

</style>
