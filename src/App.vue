<template>
  <div>
    <header-page></header-page>
    <first-part></first-part>
    <second-part></second-part>
    <br/>
        <chatbot></chatbot>

  </div>
</template>

<script>
import FirstPart from './components/FirstPart.vue'
import HeaderPage from './components/HeaderPage.vue'

import Chatbot from './components/Chatbot.vue'
import SecondPart from './components/SecondPart.vue'
import ThirdPart from './components/ThirdPart.vue'
export default {
  components:{
    HeaderPage, FirstPart,Chatbot, SecondPart, 
  }

}
</script>

<style>
@import 'bulma/css/bulma.min.css';

</style>