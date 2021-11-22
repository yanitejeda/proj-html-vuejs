<template id='main'>
    <div>
        <MainPerformance></MainPerformance>
        <MainNumberes></MainNumberes>
        <MainService></MainService>
        <MainTeam></MainTeam>
    </div>
</template>


<script>
import MainPerformance from "./main/MainPerformance.vue"
import MainNumberes from "./main/MainNumbers.vue"
import MainService from "./main/MainService.vue"
import MainTeam from "./main/MainTeam.vue"
export default {
    name:"Main",
    components:{
        MainPerformance,
        MainNumberes,
        MainService,
        MainTeam
    }
  
}
</script>
<style lang="scss">
</style>