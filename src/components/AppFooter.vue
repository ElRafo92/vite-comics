<script>
import TopFooter from './TopFooter.vue';
import MainFooter from './MainFooter.vue';
import BottomFooter from './BottomFooter.vue';

export default {
    name: 'AppFooter', 

    components: {
      TopFooter,
      MainFooter,
      BottomFooter,
    },

  data() {
    return {
      
    }
  }
}
</script>

<template>
  <TopFooter/>
  <MainFooter/>
  <BottomFooter/>
</template>

<style scoped>

</style>