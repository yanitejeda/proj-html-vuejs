<template>
  <div>
    <div class="bg-color-grey">
      <div class="Box-container py-5">
        <div class="text-g font-W6 pb-3">OUR EDITORIAL CONTENT</div>
        <h1 class="pb-3 font-W6">
          <span>Latest</span> <span class="pad-5 bord-10 text-g">News</span>
        </h1>
        <div>
          <div class="row">
            <div class="col-8">
              <p class="color-grey font-w3">Lorem ipsum dolor, sit ametvelit sint qui quas</p>
            </div>
            <div class="col-4 d-flex justify-content-end align-items-start">
              <button class="btn btn-green">SEE ALL</button>
            </div>
          </div>
        </div>

        <div class="d-flex flex-wrap justify-content-between">
          <div
            class="card my-3 bg-color-none"
            style="width: 18rem"
            v-for="(item, i) in cardItem"
            :key="i"
          >
            <!-- card box -->
            <div class="card-body">
              <div class="box-text-img color-lightW">
                <div class="news-img text-g">
                  <img :src="require(`@/assets/${item.img}`)" alt="" />
                </div>
                <h4 class="text-off-hover card-news-tittle pad-20">{{ item.textfront }}</h4>
                <div class="text-center pad-10 hover-text">
                  <div class="py-4">{{ item.user }} {{ item.time }}</div>
                  <h3 class="py-3 card-news-tittle">{{ item.textfront }}</h3>
                  <h6>{{ item.description }}</h6>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "MainNews",
  data() {
    return {
      cardItem: [
        {
          img: "news-1.jpg",
          textfront: "Increase creativity is possible for everyone",
          user: "Andrea Miller",
          time: "2 days Ago",
          description: "Lorem ipsun dolor sit amet, consectetur adipiscing elit.",
        },
        {
          img: "news-2.jpg",
          textfront: "Because market research is part of the business plan",
          user: "Lucas Miller",
          time: "2 days Ago",
          description: "Lorem ipsun dolor sit amet, consectetur adipiscing elit.",
        },
        {
          img: "news-3.jpg",
          textfront: "Working from home is now a trend",
          user: "Jessica Miller",
          time: "2 days Ago",
          description: "Lorem ipsun dolor sit amet, consectetur adipiscing elit.",
        },
      ],
    };
  },
};
</script>