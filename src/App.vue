<template>
  <div id="app">
    <pageHeader/>
    <page/>
    <pageFooter/>
  </div>
</template>

<script>
import page from '@/components/page.vue';
import pageHeader from '@/components/header.vue';
import pageFooter from '@/components/footer.vue';

export default {
  name: 'App',
  components: {
    page,
    pageHeader,
    pageFooter,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Helvetica Neue, Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
body {
    margin: 0px;
    background-color: #192974;

}
</style>
