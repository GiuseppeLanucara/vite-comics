<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppBluebar from "./components/AppBluebar.vue";
import AppFooter from "./components/AppFooter.vue";
export default {
  components: {
    AppHeader,
    AppMain,
    AppBluebar,
    AppFooter
  }
}

</script>


<template>

  <AppHeader />
  <AppMain />
  <AppBluebar />
  <AppFooter />

</template>



<style lang="scss">
@use "./styles/general.scss";
</style>