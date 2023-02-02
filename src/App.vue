<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';

export default {

    name:'App',
    data() {

        return {
          
        };

    },

    components: {

        AppHeader,
        AppMain,
        AppFooter

    },

};
</script>

<template>

  <div class="container">
      <AppHeader/>
      <AppMain/>
      <AppFooter/>
  </div>

</template>

<style lang="scss">

  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
  }
  .container {
        width: 100vw;
        height: 100vh;
    }

</style>
