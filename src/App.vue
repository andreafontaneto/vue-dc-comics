<template>
  <div>
    <Header />
    <Main />
    <BannerInfo />
    <Footer />
  </div>
</template>

<script>
import Header from "./components/Header.vue"
import Main from "./components/Main.vue"
import BannerInfo from "./components/Banner-info.vue"
import Footer from "./components/Footer.vue"

export default {
  name: 'App',
  components: {
    Header,
    Main,
    BannerInfo,
    Footer
  }
}
</script>

<style lang="scss">

  @import "./assets/style/vars.scss";
  @import "./assets/style/generals.scss";
  @import "./assets/style/utilities.scss";

</style>
