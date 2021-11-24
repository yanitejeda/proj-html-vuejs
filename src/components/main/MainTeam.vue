
<template>
  <div class="Box-container py-5">
    <div class="text-g font-W6">WE LIKE WHAT WE DO</div>

       <div class="row">
           <!-- part left -->
           <div class="col-8"> 
            <h1 class="py-3 font-W6">
            <span class="text-g font-W pad-5 bord-10">Team</span
            > <span class="h1-tittle-d">of Experts</span>
            </h1>
            <p class="font-w3 color-grey">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione nostrum
            vero nemo deserunt dignissimos provident porro.
            </p>
            
            <!-- box Card -->
            <div class="d-flex flex-wrap justify-content-between">

                <!-- card section -->
                <div class="card my-3 " style="width: 18rem " v-for="(item, i) in cardItem " :key="i">
                    <div class="card-body m-0 p-0 align-items-center d-flex row" >
                    <div class="col-5">
                        <div class="img-card">
                        <img :src="require(`@/assets/${item.img}`)" alt="" />

                        </div>
                    </div>
                    <div class="col-7">
                        <h5 class="card-title font-W6">{{item.tittle}}</h5>
                        <p class="font-w3 font-s12 color-grey">{{item.position}}</p>
                        <p class="card-text text-g"  ><span class="icon-circle" v-html="item.social1"></span> <span class="icon-circle" v-html="item.social2"></span> <span class="icon-circle" v-html="item.social3"></span></p>
                    </div>
                    </div>
                </div>
            </div>
           </div>

          <!-- part right -->
            <div class="col-4  color-lightW px-3 bord-10 back-green">
                <h5 class="pt-4 font-w6 ">President Speed</h5>
                <div>
                    <p class="pb-3 font-w3 mb-0">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eligendi consectetur ex repellat</p>
                    <p class="pb-3 font-w3 mb-0">Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas quo similique illum. Iusto, similique corrupti nobis, eum repudiandae magnam minima.</p>
                    <p class="pb-3 font-w3 mb-0">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum perferendis voluptatibus illo porro ndis voluptati ndis voluptatindis voluptati </p>

                </div>
                <h6 class="pt-5 font-w6">T.Johnson</h6>

            </div>
       </div>
  </div>
</template>
<script>
export default {
  name: "MainTeam",
  data(){
      return{
          cardItem :[
              {
                  img:"team-1.jpg",
                  tittle:"David Cooper",
                  position: "CTO & CC-FOUNDER",
                  social1: '<i class="fab fa-facebook-f"></i>',
                  social2:'<i class="fab fa-twitter"></i>',
                  social3:"<i class='fab fa-linkedin-in'></i>",
              }, {
                  img:"team-2.jpg",
                  tittle:"David Cooper",
                  position: "CTO & CC-FOUNDER",
                  social1: '<i class="fab fa-facebook-f"></i>',
                  social2:'<i class="fab fa-twitter"></i>',
                  social3:"<i class='fab fa-linkedin-in'></i>",
              }, {
                  img:"team-3.jpg",
                  tittle:"David Cooper",
                  position: "CTO & CC-FOUNDER",
                  social1: '<i class="fab fa-facebook-f"></i>',
                  social2:'<i class="fab fa-twitter"></i>',
                  social3:"<i class='fab fa-linkedin-in'></i>",
              }, {
                  img:"team-4.jpg",
                  tittle:"David Cooper",
                  position: "CTO & CC-FOUNDER",
                  social1: '<i class="fab fa-facebook-f"></i>',
                  social2:'<i class="fab fa-twitter"></i>',
                  social3:"<i class='fab fa-linkedin-in'></i>",
              }, 
          ]
      }
  }
};
</script>