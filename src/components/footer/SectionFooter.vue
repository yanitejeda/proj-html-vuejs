<template>

<div>
     <div class="bg-img-footer">
        <div class="Box-container py-5 color-lightW d-flex gap-3">
        

            <div class="card card-s my-3 py-3 bg-card-footer-n col-3">
            <div class="card-body">
                <div>
                <h4>logo</h4>
            
                </div>
                <p>
                    Lorem ipsum dolor, sit ametvelit sint qui qu
                </p>
                
                <p class="card-text ">
                +(305) 1234-5679
                </p>
                
                <p class="card-text ">
                    icon hello@example.com
                </p>
                
                <p class="card-text ">
                icon Main Avenue, 987
                </p>
                <button class="btn btn-light">GET IN TOUCH</button>
                
            </div>
            </div>
        

            <!-- section card -->
            
                <div class="card card-s my-3 py-3 bg-card-footer col-3"  v-for="(item, i) in footerItem" :key="i">
                    <div class="card-body">
                        <div>
                        <h4>{{item.tittle}}</h4>
                    
                        </div>
                        
                        <p class="card-text ">
                            {{item.info1}}
                        </p>
                        <p class="card-text ">
                            {{item.info2}}
                        </p>
                        <p class="card-text ">
                            {{item.info3}}
                        </p>
                        <p class="card-text ">
                            {{item.info4}}
                        </p>
                        <p class="card-text ">
                            {{item.info5}}
                        </p>
                        <p class="card-text ">
                            {{item.info6}}
                        </p>
                        
                    </div>
                </div>
            



        </div>
    </div>


    <!-- bar footer -->
    <div class="back-GB">
        <div class="Box-container justify-content-between py-3 color-lightW d-flex gap-3">
            <div>kkfnkafnkanfkanfka</div>
            <div>bfjabfjabfjabfjab</div>
        

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