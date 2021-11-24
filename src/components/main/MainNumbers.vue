<template>
    <div class="bg-img-numbers">

        <div class="Box-container text-center py-5 color-lightW">
            <div class="text-g font-W6 pb-3">what are we doing </div>
            <h1 class="pb-5 font-W6"><span class=" pad-5 bord-10">Results</span> <span>in Numbers</span> </h1>
            <ul class="d-flex justify-content-between py-3">

                <li v-for="(item, i) in numberList" :key="i">
                    <h4 class="text-g font-W6">{{item.num}}</h4>
                    <h5 class="font-W6">{{item.tittle}}</h5>    
                </li>
            </ul>

        </div>
    </div>
    
</template>
<script>
export default {
    name:"MainNumberes",
    data(){
        return {
          numberList:[
              {
                  num:"128",
                  tittle:"Certifications"
              },
               {
                  num:"230",
                  tittle:"Employees"
              },
               {
                  num:"128",
                  tittle:"Certifications"
              },
               {
                  num:"571",
                  tittle:"Customers"
              },
               {
                  num:"94",
                  tittle:"Countries Served"
              },
          ]  
        }
    }
}
</script>