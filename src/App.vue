<template>
  <div>
    <header-page></header-page>
    <first-part></first-part>
  </div>
</template>

<script>
import FirstPart from './components/FirstPart.vue'
import HeaderPage from './components/HeaderPage.vue'
export default {
  components:{
    HeaderPage, FirstPart
  }

}
</script>

<style>
@import 'bulma/css/bulma.min.css';

</style>