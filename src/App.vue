<script>
import AppHeader from './components/AppHeader.vue';
import AppFooter from './components/AppFooter.vue';

  export default{
    components: { AppHeader, AppFooter }
}

</script>

<template>
  
  <AppHeader/>

  <router-view></router-view>
  
  <AppFooter/>

</template>

<style lang="scss">
@use './style/general.scss' as *;
</style>
