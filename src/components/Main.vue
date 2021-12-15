<template>
    <main>
        <Jumbotron/>
        <Clients/>
        <CloudBasedFinance/>
        <SpecialtyServices/>
        <InvestmentsNumbers/>
        <ClientFeedback/>
    </main>
</template>

<script>
import Jumbotron from './Jumbotron.vue'
import Clients from './Clients.vue'
import CloudBasedFinance from './CloudBasedFinance.vue'
import SpecialtyServices from './SpecialtyServices.vue'
import InvestmentsNumbers from './InvestmentsNumbers.vue'
import ClientFeedback from './ClientFeedback.vue'


export default {
  components: { 
    Jumbotron,
    Clients,
    CloudBasedFinance,
    SpecialtyServices,
    InvestmentsNumbers,
    ClientFeedback
  },

  name: 'Main'

}
</script>


<style scoped lang="scss">

</style>
