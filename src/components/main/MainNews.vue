<template>
  <div>
    <div>
      <div class="Box-container py-5">
        <div class="text-g pb-3">OUR EDITORIAL CONTENT</div>
        <h1 class="pb-5">
          <span>Latest</span><span class="pad-5 text-g">News</span>
        </h1>
        <div>
          <div class="row">
            <div class="col-8">
              <p>Lorem ipsum dolor, sit ametvelit sint qui quas</p>
            </div>
            <div class="col-4 d-flex justify-content-end align-items-start">
              <button class="btn btn-green">SEE ALL</button>
            </div>
          </div>
        </div>

        <div class="d-flex flex-wrap justify-content-between">
          <div
            class="card my-3 py-3"
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
                <h4 class="text-off-hover">{{ item.textfront }}</h4>
                <div class="text-center hover-text">
                  <div class="py-4">{{ item.user }} {{ item.time }}</div>
                  <h3 class="py-3">{{ item.textfront }}</h3>
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
          textfront: "loremjjnjnjnjnjn",
          user: "icona1",
          time: "icona2",
          description: "bbbjbj",
        },
        {
          img: "news-2.jpg",
          textfront: "loremjjnjnjnjnjn",
          user: "icona1",
          time: "icona2",
          description: "bbbjbj",
        },
        {
          img: "news-3.jpg",
          textfront: "loremjjnjnjnjnjn",
          user: "icona1",
          time: "icona2",
          description: "bbbjbj",
        },
      ],
    };
  },
};
</script>