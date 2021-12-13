<template>
    <main>
        <Jumbotron/>
        <Clients/>
        <CloudBasedFinance/>
    </main>
</template>

<script>
import Jumbotron from './Jumbotron.vue'
import Clients from './Clients.vue'
import CloudBasedFinance from './CloudBasedFinance.vue'


export default {
  components: { 
    Jumbotron,
    Clients,
    CloudBasedFinance
  },

  name: 'Main'

}
</script>


<style scoped lang="scss">

</style>
