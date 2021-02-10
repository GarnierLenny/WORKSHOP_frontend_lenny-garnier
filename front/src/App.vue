<template>
  <div id="app">
    <HeaderBar></HeaderBar>
    <router-view/>
  </div>
</template>

<script>
  import HeaderBar from './components/HeaderBar'
  export default {
    components: { HeaderBar }
  }
</script>

<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Lobster&display=swap');
* {
  font-size: 125%;
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

</style>
