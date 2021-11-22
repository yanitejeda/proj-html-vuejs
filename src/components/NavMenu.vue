<template>
  <div class="">
      <div class="Box-container">
           <nav class="nav d-flex justify-content-between align-items-center py-3">
               <div class="d-flex color-lightW">
                   <li>
                     NexGen
                   </li>    
               </div>
                <div class="d-flex">
                  <!--  <li>
                       <a class="nav-link active" aria-current="page" href="#">Active</a> 
                   </li> -->
                   <li v-for="(item, i) in navItem" :key="i">
                     <a class="nav-link color-lightW" href="#">{{item.navInfo}}</a>
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
                  navInfo : "ICONA"
              }
          ]
      }
  }
};
</script>
<style lang="scss">

</style>