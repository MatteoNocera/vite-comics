<script>
import AppHeader from './components/AppHeader.vue';
import AppJumbo from './components/AppJumbo.vue';
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
    AppJumbo,
    AppMain,
    AppBuy,
    AppLinks,
    AppFoot,

  }
}
</script>

<template>
  <AppHeader></AppHeader>

  <AppJumbo></AppJumbo>

  <AppMain></AppMain>

  <AppBuy></AppBuy>

  <AppLinks></AppLinks>

  <AppFoot></AppFoot>
</template>

<style lang="scss"></style>
