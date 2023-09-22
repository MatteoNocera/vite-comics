<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppBuy from './components/AppBuy.vue';


export default {
  name: 'App',
  Data() {
    return {};
  },
  components: {
    AppHeader,
    AppMain,
    AppBuy
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <AppMain></AppMain>

  <AppBuy></AppBuy>

  <footer id="app_footer"></footer>
  <!-- /#app_footer -->
</template>

<style lang="scss"></style>
