<template>
  <div id="header">
    <div class="bg-img">
      <NavBar></NavBar>
      <NavMenu></NavMenu>
      <PresentationPage></PresentationPage>
    </div>
  </div>
</template>
<script>
import NavBar from "./NavBar.vue";
import NavMenu from "./NavMenu.vue";
import PresentationPage from "./PresentationPage.vue"
export default {
  name: "Header",
  components: {
    NavBar,
    NavMenu,
    PresentationPage,
  },
};
</script>

<style lang="scss">
</style>