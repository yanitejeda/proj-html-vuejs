<template>
  <div class="nav-bgc">
      <div class="Box-container">
           <nav class="nav d-flex justify-content-between align-items-center">
               <div class="d-flex color-lightW">
                   <li>
                      <span>Open Hours:Mon-sat-9:00-18:00</span>
                   </li>    
               </div>
                <div class="d-flex">
                  <!--  <li>
                       <a class="nav-link active" aria-current="page" href="#">Active</a> 
                   </li> -->
                   <li v-for="(item, i) in navItem" :key="i">
                     <a class="nav-link color-lightW" href="#">{{item.navInfo}}</a>
                   </li>  
               </div>
               
            </nav>
      </div>
   
  </div>
</template>
<script>
export default {
  name: "NavBar",
  data(){
      return{
          navItem:[
              {
                  navInfo : "+1(305) 1234-5678"
              },
              {
                  navInfo : "hello@example.com"
              },
              {
                  navInfo : "F"
              },
              {
                  navInfo : "T"
              },
              {
                  navInfo : "IN"
              }
          ]
      }
  }
};
</script>