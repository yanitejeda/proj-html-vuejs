<template>

<div>
     <div class="bg-img-footer">
        <div class="Box-container py-5 color-lightW d-flex gap-3">
        

            <div class="card card-s my-3 py-3 bg-card-footer-n col-3">
            <div class="card-body">
                <div>
                <h4><span class=" borde-left"> NEX</span><span class="color-lightG">GEN</span></h4>
            
                </div>
                <p class="font-w3 color-grey">
                    Lorem ipsum dolor, sit ametvelit sint qui qu
                </p>
                
                <p class="card-text font-w3 color-grey ">
                <i class="fas fa-phone-alt"></i> +(305) 1234-5679
                </p>
                
                <p class="card-text font-w3 color-grey ">
                  <i class="fas fa-envelope"></i>   hello@example.com
                </p>
                
                <p class="card-text font-w3 color-grey ">
                <i  class="fas fa-map-marker-alt"></i> Main Avenue, 987
                </p>
                <button class="btn btn-light">GET IN TOUCH</button>
                
            </div>
            </div>
        

            <!-- section card -->
            
                <div class="card card-s my-3 py-3 bg-card-footer col-3"  v-for="(item, i) in footerItem" :key="i">
                    <div class="card-body">
                        <div>
                        <h4 class="font-W6">{{item.tittle}}</h4>
                    
                        </div>
                        
                        <p class="card-text font-w3 color-grey">
                            {{item.info1}}
                        </p>
                        <p class="card-text font-w3 color-grey">
                            {{item.info2}}
                        </p>
                        <p class="card-text font-w3 color-grey">
                            {{item.info3}}
                        </p>
                        <p class="card-text font-w3 color-grey">
                            {{item.info4}}
                        </p>
                        <p class="card-text font-w3 color-grey">
                            {{item.info5}}
                        </p>
                        <p class="card-text font-w3 color-grey">
                            {{item.info6}}
                        </p>
                        
                    </div>
                </div>
            



        </div>
    </div>


    <!-- bar footer -->
    <div class="back-GB">
        <div class="Box-container justify-content-between py-3 color-lightW d-flex gap-3">
            <div class="font-w3 color-grey">Lorem ipsum dolor, sit ametvelit sint qui qu</div>
            <div class="font-w3 color-grey">sit ametvelit sint qui qu</div>
        

        </div>
    </div>


</div>

 
</template>
<script>
export default {
  name: "SectionFooter",
  data() {
      return{
          footerItem:[
             
            {
                tittle:"About",
                info1:"The Company",
                info2:"The Company",
                info3:"The Company",
                info4:"The Company",
                info5:"The Company",
                info6:"The Company",
            },   {
                tittle:"Service",
                info1:"The Company",
                info2:"The Company",
                info3:"The Company",
                info4:"The Company",
                info5:"The Company",
                info6:"The Company",
            },   {
                tittle:"Support",
                info1:"The Company",
                info2:"The Company",
                info3:"The Company",
                info4:"The Company",
                info5:"The Company",
                info6:"The Company",
            },
          ]
      }
        
    },
};
</script>