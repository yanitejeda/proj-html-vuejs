<template>
  <div class="">
      <div class="Box-container">
           <nav class="nav d-flex justify-content-between align-items-center py-3">
               <div class="d-flex color-lightW">
                   <li class="font-w3">
                       <span class=" borde-left"> NEX</span><span class="color-lightG">GEN</span>
                    
                   </li>    
               </div>
                <div class="d-flex">
                   <li v-for="(item, i) in navItem" :key="i">
                     <a class="nav-link color-lightW" href="#" v-html="item.navInfo"></a>
                   </li>  
                   <button class="btn btn-green">GET IN TOUCH</button>
               </div>
               
            </nav>
      </div>
   
  </div>
</template>
<script>
export default {
  name: "NavMenu",
  data(){
      return{
          navItem:[
              {
                  navInfo : "HOME"
              },
              {
                  navInfo : "ABOUT"
              },
              {
                  navInfo : "SERVICES"
              },
              {
                  navInfo : "TEAM"
              },
              {
                  navInfo : "BLOG"
              },
               {
                  navInfo : "<i class='far fa-user'></i>"
              }
          ]
      }
  }
};
</script>
<style lang="scss">

</style>