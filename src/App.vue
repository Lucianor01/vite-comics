<script >
import HeaderComp from './components/HeaderComp.vue';
import MainHeader from './components/MainHeader.vue';
import MainComp from './components/MainComp.vue';
import FooterComp from './components/FooterComp.vue';

export default {
  name: "App",
  components: {
    HeaderComp,
    MainHeader,
    MainComp,
    FooterComp
  }
}
</script>
<template>
  <HeaderComp />
  <main>
    <MainHeader />
    <MainComp />
  </main>
  <FooterComp />
</template>

<style lang="scss">
@use "./style/main.scss" as *;
</style>
