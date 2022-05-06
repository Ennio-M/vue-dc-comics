<template>
  <div id="app">
    <app-header :menu="header"/>
    <AppMain/>
    <AppFooter/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader.vue'
import AppMain from './components/AppMain.vue'
import AppFooter from './components/AppFooter.vue'

export default {
  name: 'App',
  components: {
    AppHeader,
    AppMain,
    AppFooter
  },
  data() {
      return {
          header: [
            {
              text: 'Characters',
              active: false
            },
            {
              text: 'Comics',
              active: true
            },
            {
              text: 'Movies',
              active: false
            },
            {
              text: 'TV',
              active: false
            },
            {
              text: 'Games',
              active: false
            },
            {
              text: 'Collectibles',
              active: false
            },
            {
              text: 'Videos',
              active: false
            },
            {
              text: 'Fans',
              active: false
            },
            {
              text: 'News',
              active: false
            },
            {
              text: 'Shop',
              active: false
            }
          ]
      }
  }
}
</script>

<style lang="scss">
  @import './style/variables.scss';
  @import './style/general.scss';
</style>
