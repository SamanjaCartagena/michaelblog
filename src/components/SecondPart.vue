<template>

 <div class="container ">
  <div class="new">
   <p style='font-size:25px; font-family:Papyrus; padding-top:20px;'><strong>New Agents</strong></p>
  </div>
   <center><hr style='border:.5px solid #d5a341; width:95%'/></center>
   <div class="columns">
  <div class="column">
    <img :src="this.suit1" class='sameline'/>
    <p>What to wear in a closing</p>
  </div>
  <div class="column">
    <img :src='this.house' class='sameline'/>
        <p>When can you start selling houses</p>

  </div>
  <div class="column">
  <img :src='this.commercial' class='sameline'/>
        <p>Commerical Real Estate</p>
  </div>
  <div class="column">
  <img :src='this.retail' class='sameline'/>
        <p>How to deal with retail </p>  </div>
</div>
</div>
</template>

<script>
import suit1 from '../assets/suit1.png'
import house from '../assets/house.jpg'
import commercial from '../assets/commercial.jpg'
import retail from '../assets/retail.jpg'
export default {
  data(){
    return{
      suit1:suit1,
      house:house,
      commercial:commercial,
      retail:retail
    }
  }

}
</script>

<style scoped>
.container{
  height:400px;
}
.new{
  background-color: white;
  color:black;
}
.sameline{
  width:100%;
  height:400px;
}
</style>