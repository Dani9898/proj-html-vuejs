<template>
    <main>
        <Jumbotron/>
        <Clients/>
        <CloudBasedFinance/>
        <SpecialtyServices/>
    </main>
</template>

<script>
import Jumbotron from './Jumbotron.vue'
import Clients from './Clients.vue'
import CloudBasedFinance from './CloudBasedFinance.vue'
import SpecialtyServices from './SpecialtyServices.vue'


export default {
  components: { 
    Jumbotron,
    Clients,
    CloudBasedFinance,
    SpecialtyServices
  },

  name: 'Main'

}
</script>


<style scoped lang="scss">

</style>
