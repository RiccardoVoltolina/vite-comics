<script>

  import AppHeader from './components/AppHeader.Vue'
  import AppMainContent from './components/AppMainContent.vue'
  import AppJumbotron from './components/appJumbotron.vue'
  import AppFooter1 from './components/AppFooter1.Vue'
  import AppFooter2 from './components/AppFooter2.Vue'


  export default{
    name:'App',
    data() {
      return {
      }
    },
    components: {
      AppHeader,
      AppMainContent,
      AppJumbotron,
      AppFooter1,
      AppFooter2,
    }

  }
</script>

<template>
  <AppHeader/>
  <AppMainContent/>
  <AppJumbotron/>
  <AppFooter1/>
  <AppFooter2/>

</template>

<style>
</style>
