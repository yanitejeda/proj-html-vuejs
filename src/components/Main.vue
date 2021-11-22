<template id='main'>
    <div>
        <MainPerformance></MainPerformance>
        <MainNumberes></MainNumberes>
        <MainService></MainService>
    </div>
</template>


<script>
import MainPerformance from "./main/MainPerformance.vue"
import MainNumberes from "./main/MainNumbers.vue"
import MainService from "./main/MainService.vue"
export default {
    name:"Main",
    components:{
        MainPerformance,
        MainNumberes,
        MainService
    }
  
}
</script>
<style lang="scss">
</style>