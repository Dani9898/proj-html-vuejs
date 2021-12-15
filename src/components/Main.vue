<template>
    <main>
        <Jumbotron/>
        <Clients/>
        <CloudBasedFinance/>
        <SpecialtyServices/>
        <InvestmentsNumbers/>
        <ClientFeedback/>
        <ReadyToTalk/>
    </main>
</template>

<script>
import Jumbotron from './Jumbotron.vue'
import Clients from './Clients.vue'
import CloudBasedFinance from './CloudBasedFinance.vue'
import SpecialtyServices from './SpecialtyServices.vue'
import InvestmentsNumbers from './InvestmentsNumbers.vue'
import ClientFeedback from './ClientFeedback.vue'
import ReadyToTalk from './ReadyToTalk.vue'


export default {
  components: { 
    Jumbotron,
    Clients,
    CloudBasedFinance,
    SpecialtyServices,
    InvestmentsNumbers,
    ClientFeedback,
    ReadyToTalk
  },

  name: 'Main'

}
</script>


<style scoped lang="scss">

</style>
