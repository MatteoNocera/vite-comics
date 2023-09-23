<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppBuy from './components/AppBuy.vue';
import AppLinks from './components/AppLinks.vue';
import AppFoot from './components/AppFoot.vue';


export default {
  name: 'App',
  data() {
    return {

    };
  },
  components: {
    AppHeader,
    AppMain,
    AppBuy,
    AppLinks,
    AppFoot,
  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <AppMain></AppMain>

  <AppBuy></AppBuy>

  <AppLinks></AppLinks>

  <AppFoot></AppFoot>
</template>

<style lang="scss"></style>
