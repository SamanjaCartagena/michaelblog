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
export default {

}
</script>

<style>

</style>