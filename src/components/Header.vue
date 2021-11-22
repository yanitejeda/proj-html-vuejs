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
import NavBar from "./header/NavBar.vue"
import NavMenu from "./header/NavMenu.vue"
import PresentationPage from "./header/PresentationPage.vue"
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