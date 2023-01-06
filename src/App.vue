<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';


export default {
  components: {
   AppHeader,
   AppMain,
   AppFooter
  }
}
</script>

<template>
  <div>
    <div>
      <AppHeader />
      <AppMain />
      <AppFooter />
    </div>
  </div>
</template>

<style >
  *{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
</style>
