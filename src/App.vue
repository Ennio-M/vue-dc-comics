<template>
  <div id="app" class="container">
    <AppHeader/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'

export default {
  name: 'App',
  components: {
    AppHeader
  }
}
</script>

<style lang="scss">
  @import './style/variables.scss';
  @import './style/general.scss';

  .container{
    width: 75%;
    margin: 0 auto;
  }
</style>
