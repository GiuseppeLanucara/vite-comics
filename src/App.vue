<script>
import AppHeader from "./components/AppHeader.vue";
import AppMain from "./components/AppMain.vue";
import AppBluebar from "./components/AppBluebar.vue";
import AppFooter from "./components/AppFooter.vue";
import AppContacts from "./components/AppContacts.vue";

export default {
  components: {
    AppHeader,
    AppMain,
    AppBluebar,
    AppFooter,
    AppContacts
  }
}

</script>


<template>

  <AppHeader />
  <AppMain />
  <AppBluebar />
  <AppFooter />
  <AppContacts />

</template>



<style lang="scss">
@use "./styles/general.scss";
</style>