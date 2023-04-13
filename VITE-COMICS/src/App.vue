<template>
  <div class="">
    <AppHeader/>
    <AppMain/>
    <AppFooter/>
    
  </div>
</template>

<script>
import AppHeader from './components/Appheader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {
    components: { AppHeader, AppFooter, AppMain }
  }
</script>

<style lang="scss" scoped>

</style>