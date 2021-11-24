<template>
  <div class="back-GB">
    <div class="Box-container py-5 color-lightW">
      <div class="text-g font-W6 pb-3">what are we doing</div>
      <h1 class="pb-5">
        <span>Excellence in</span> <span class="pad-5 bord-10">Services</span>
      </h1>
      <div>
        <div class="row">
          <div class="col-8">
            <p class="font-w3">
              Lorem ipsum dolor, sit amet conex quaerat velit sint qui quas hic
              placeat nam nostrum, reprehenderit doloremque fugiat obcaecati.
            </p>
          </div>
          <div class="col-4 d-flex justify-content-end align-items-start">
            <button class="btn btn-green">SEE ALL</button>
          </div>
        </div>
      </div>

   <div class="d-flex flex-wrap justify-content-between ">
          <div class="card my-3 py-3 bg-card" style="width: 18rem" v-for="(item, i) in cardItem " :key="i">
        <div class="card-body ">
            <div class="justify-content-between text-g d-flex">
                 <h4>{{item.icon}}</h4>
                 <span>Freccia</span>
            </div>
            <h5 class="card-title font-W6">{{item.tittle}}</h5>
            <p class="card-text font-w3 py-3">
                {{item.text}}
            </p>
        </div>
      </div>
   </div>

    </div>
  </div>
</template>
<script>
export default {
  name: "MainService",
  data() {
    return {
      cardItem: [
        {
          icon: "icona",
          tittle: "Audit & Assurance",
          text:"Lorem ipsum dolor sit amet consectetur adipisicing elit."
        },
        {
          icon: "icona",
          tittle: "Financial Advisory",
          text:"Lorem ipsum dolor sit amet consectetur adipisicing elit."
        },
        {
          icon: "icona",
          tittle: "Analytics and M&A",
          text:"Lorem ipsum dolor sit amet consectetur adipisicing elit."
        },
        {
          icon: "icona",
          tittle: "Middle Marketing",
          text:"Lorem ipsum dolor sit amet consectetur adipisicing elit."
        },
        {
           icon: "icona",
          tittle: "Legal Consulting",
          text:"Lorem ipsum dolor sit amet consectetur adipisicing elit."
         },
        {
          icon: "icona",
          tittle: "Regulatory Risk",
          text:"Lorem ipsum dolor sit amet consectetur adipisicing elit."
         },
      ],
    };
  },
};
</script>