<template id='main'>
    <div>
        <MainPerformance></MainPerformance>
        <MainNumberes></MainNumberes>
        <MainService></MainService>
        <MainTeam></MainTeam>
        <MainNews></MainNews>
        <MainNLetter></MainNLetter>
        <MainSendMessage></MainSendMessage>
    </div>
</template>


<script>
import MainPerformance from "./main/MainPerformance.vue"
import MainNumberes from "./main/MainNumbers.vue"
import MainService from "./main/MainService.vue"
import MainTeam from "./main/MainTeam.vue"
import MainNews from "./main/MainNews.vue"
import MainNLetter from "./main/MainNLetter.vue"
import MainSendMessage from "./main/MainSendMessage.vue"

export default {
    name:"Main",
    components:{
        MainPerformance,
        MainNumberes,
        MainService,
        MainTeam,
        MainNews,
        MainNLetter,
        MainSendMessage
    }
  
}
</script>
<style lang="scss">
</style>