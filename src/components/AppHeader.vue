<script>
import AppLogo from './AppLogo.vue';
import ListHeader from './ListHeader.vue';

export default {
    name: 'AppHeader', 

    components: {
        AppLogo,
        ListHeader,
    },

  data() {
    return {
      
    }
  }
}
</script>

<template>
  <header class="container">
        <AppLogo/>
        <ListHeader/>
  </header>
</template>

<style scoped>
  header {
    display: flex;
    justify-content: space-between;
    width: 100%;
}
.container{
    max-width: 1200px;
    margin: auto;
}

</style>