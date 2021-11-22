
<template>
  <div class="Box-container py-5">
    <div class="text-g">WE LIKE WHAT WE DO</div>

       <div class="row">
           <!-- part left -->
           <div class="col-8"> 
            <h1 class="py-3">
            <span class="text-g pad-5">Team</span
            ><span class="h1-tittle-d">of Experts</span>
            </h1>
            <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Ratione nostrum
            vero nemo deserunt dignissimos provident porro, laudantium veniam quam
            iusto incidunt aliquid quasi distinctio impedit. Dolores eum accusantium
            facere repellendus!
            </p>
            
            <!-- box Card -->
            <div class="d-flex flex-wrap justify-content-between">

                <!-- card section -->
                <div class="card" style="width: 18rem " v-for="(item, i) in cardItem " :key="i">
                    <div class="card-body d-flex row" >
                    <div class="col-5">
                        <div class="img-card">
                        <!-- <img :src="require('@/assets/' + item.img)" alt="" /> -->
                        </div>
                    </div>
                    <div class="col-7">
                        <h5 class="card-title">{{item.tittle}}</h5>
                        <h4>{{item.position}}</h4>
                        <p class="card-text py-3">{{item.social1}} {{item.social2}} {{item.social3}}</p>
                    </div>
                    </div>
                </div>
            </div>
           </div>

          <!-- part right -->
            <div class="col-4 back-green">
                <h5>President Speed</h5>
                <p>
                    <span>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Eligendi consectetur ex repellat magni eveniet, debitis assumenda ad illum? Delectus dolor eni</span>
                    <span>Lorem ipsum dolor sit amet consectetur adipisicing elit. Voluptas quo similique illum. Iusto, similique corrupti nobis, eum repudiandae magnam minima.</span>
                    <span>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum perferendis voluptatibus illo porro ab quos ipsum blanditiis doloremque fugiat consequuntur rem in par</span>

                </p>
                <h6>T.Johnson</h6>

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
                  img:"team-1.gpg",
                  tittle:"David Cooper",
                  position: "CTO & CC-FOUNDER",
                  social1: "f",
                  social2:"t",
                  social3:"in",
              }, {
                  img:"team-2.gpg",
                  tittle:"David Cooper",
                  position: "CTO & CC-FOUNDER",
                  social1: "f",
                  social2:"t",
                  social3:"in",
              }, {
                  img:"team-3.gpg",
                  tittle:"David Cooper",
                  position: "CTO & CC-FOUNDER",
                  social1: "f",
                  social2:"t",
                  social3:"in",
              }, {
                  img:"team-4.gpg",
                  tittle:"David Cooper",
                  position: "CTO & CC-FOUNDER",
                  social1: "f",
                  social2:"t",
                  social3:"in",
              }, 
          ]
      }
  }
};
</script>