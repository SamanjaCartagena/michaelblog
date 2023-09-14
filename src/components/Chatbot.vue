<template>
  <div>
  <div id="box" @click='chatroom=true' v-if='!chatroom'>
   <center><p class='chat'> Chat with us</p></center>

  </div>
  <div id='box1' v-if='chatroom' v-click-outside="onClickOutside">
      <center><p class='chatroomchat'> Chat with us</p></center>
 <hr style=' border:1px solid white'/>

  </div>
  </div>
</template>

<script>

export default {
    data(){
        return{
            chatroom:false
        }
    },
    methods:{
        onClickOutside(){
            this.chatroom=false
        }
    }
    

}
</script>

<style scoped>
#box{
    width:150px;
    position: fixed;
    height:50px;
    border:1px solid #d5a341;
    border-radius:2px;
    bottom:0px;
    right:10px;
    padding-top:5px;
    background-color: black;
    color:#d5a341;

}
#box:hover{
    cursor:pointer;
}
#box1{
    height:600px;
    width:350px;
    background-color: black;
    color:white;
    position: fixed;
    bottom:0px;
    right:10px;
    border:1px solid #d5a341;
}
.chat{
    padding:5px;
}
</style>