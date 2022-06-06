<template>
  <div id="app">
    <DCheader/>
    <DCmain/>
    <DCfooter/>
  </div>
</template>

<script>
import DCheader from './components/DCheader'
import DCmain from './components/DCmain'
import DCfooter from './components/DCfooter'
export default { 
  name: 'App',
  components: {
  DCheader,
  DCmain,
  DCfooter,
  }
}
</script>

<style lang="scss">
@import './assets/style/global.scss';
</style>
