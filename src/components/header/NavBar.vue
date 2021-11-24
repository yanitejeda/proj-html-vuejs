<template>
  <div class="nav-bgc">
      <div class="Box-container">
           <nav class="nav font-s12 d-flex justify-content-between align-items-center">
               <div class="d-flex color-lightG">
                   <li>
                      <span> <i class="fas fa-clock"></i> Open Hours:Mon-sat-9:00-18:00</span>
                   </li>    
               </div>
                <div class="d-flex">
                  <!--  <li>
                       <a class="nav-link active" aria-current="page" href="#">Active</a> 
                   </li> -->
                   <li v-for="(item, i) in navItem" :key="i">
                     <a class="nav-link color-lightG" href="#" v-html="item.navInfo"></a>
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
                  navInfo : '<i class="fas fa-phone-alt"></i> +1(305) 1234-5678'
              },
              {
                  navInfo : '<i class="fas fa-envelope"></i> hello@example.com'
              },
              {
                  navInfo : '<i class="fab fa-facebook-f"></i>'
              },
              {
                  navInfo : '<i class="fab fa-twitter"></i>'
              },
              {
                  navInfo : "<i class='fab fa-linkedin-in'></i>"
              }
          ]
      }
  }
};
</script>