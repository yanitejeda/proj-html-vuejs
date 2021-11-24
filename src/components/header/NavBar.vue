<template>
  <div class="nav-bgc">
      <div class="Box-container">
           <nav class="nav d-flex justify-content-between align-items-center">
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
                     <a class="nav-link color-lightG" href="#">{{item.navInfo}}</a>
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
                  navInfo : ' +1(305) 1234-5678'/* <i class="fas fa-phone-alt"></i> */
              },
              {
                  navInfo : ' hello@example.com'/* <i class="fas fa-envelope"></i> */
              },
              {
                  navInfo : 'f'/* <i class="fab fa-facebook-f"></i> */
              },
              {
                  navInfo : 't'/* <i class="fab fa-twitter"></i> */
              },
              {
                  navInfo : "in"/* <i class='fab fa-linkedin-in'></i> */
              }
          ]
      }
  }
};
</script>