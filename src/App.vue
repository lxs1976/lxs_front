<template>
  <div>
    <div>
    <Header class="mb-5"></Header>
  </div>
  <div class="container context">
    <router-view key="this.$route.fullPath"></router-view>
  </div>
  </div>
</template>

<style>

</style>
<script>
import Header from "@/componments/Layout/Header";
export default {
  name: 'app',
  components: {Header}
}
</script>