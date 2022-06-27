<template>
  <div>
    <div>
    <Header class="mb-5"></Header>
  </div>
  <div class="container context">
    <router-view key="this.$route.fullPath"></router-view>
  </div>
    <Footer></Footer>
  </div>
</template>

<style>

</style>
<script>
import Header from "@/componments/Layout/Header";
import Footer from "@/componments/Layout/Footer";
export default {
  name: 'app',
  components: {Footer, Header}
}
</script>