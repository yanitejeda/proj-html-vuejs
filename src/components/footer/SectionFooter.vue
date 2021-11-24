<template>

<div>
     <div class="bg-img-footer">
        <div class="Box-container py-5 color-lightW d-flex gap-3">
        
<!-- card conn info contatti -->
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
                    <i class="fas fa-envelope"></i>hello@example.com
                    </p>
                    
                    <p class="card-text font-w3 color-grey ">
                    <i  class="fas fa-map-marker-alt"></i> Main Avenue, 987
                    </p>
                    <button class="btn btn-light">GET IN TOUCH</button>
                    
                </div>
            </div>
        
<!-- card conn info elenco -->            
                <!-- <div class="card card-s my-3 py-3 bg-card-footer col-3"  v-for="(item, i) in footerItem" :key="i">                    <div class="card-body">

                        <h4 class="font-W6">{{item.tittle}}</h4>
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
                </div> -->
            <FooterInformation v-for="(item, i) in footerItem" :key="i"
            :tittle='item.tittle'
            :info1='item.info1'
            :info2='item.info2'
            :info3='item.info3'
            :info4='item.info4'
            :info5='item.info5'
            :info6='item.info6'
            >

            </FooterInformation>



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
import FooterInformation from "./FooterInformation.vue"
export default {
  name: "SectionFooter",
  components:{FooterInformation},
  data() {
      return{
          footerItem:[
             
            {
                tittle:"About",
                info1:"The Company",
                info2:"Institutional",
                info3:"Social & Events",
                info4:"Innovation",
                info5:"Enviroment",
                info6:"Tecnology",
            },   {
                tittle:"Service",
                info1:"Audit & Assurance",
                info2:"Financial Advisor",
                info3:"Analytics M&A",
                info4:"Middle Marketing",
                info5:"Legal Consulting",
                info6:"Regulatory Risk",
            },   {
                tittle:"Support",
                info1:"Responsability",
                info2:"Terms of Use",
                info3:"About Cookies",
                info4:"Privacy Policy",
                info5:"Accessibility",
                info6:"Information",
            },
          ]
      }
        
    },
};
</script>