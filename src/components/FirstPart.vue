<template>
  <div class="first">
    <div style="background-color:black; width:75%;
    height:500px;">
    <img :src="this.background" style="width:100%; height:700px;"  />
    </div>
    <div style=' width:30%; height:700px;'>
        <p class='follow' @click="drawer=true">FOLLOW</p>
        <el-drawer  v-model="drawer" title="I am the title" :with-header="false">
         <p style='padding-top:80px; padding-left:40px;font-family: Papyrus; font-size:25px;'><strong>Follow me on</strong></p>
        <button class='iconbtn'><img :src="this.twitter" class='iconimage'/>Twitter</button><br/>
        <button class='iconbtn'><img :src="this.facebook" class='iconimage'/>Facebook</button><br/>
        <button class='iconbtn'><img :src="this.instagram" class='iconimage'/>Instagram</button><br/>
        <button class='iconbtn'><img :src="this.tiktok" class='iconimage'/>Tiktok</button><br/>
                <button class='iconbtn'><img :src="this.pinterest" class='iconimage'/>Pinterest</button><br/>
                                <button class='iconbtn'><img :src="this.linkedin" class='iconimage'/>Linkedin</button><br/>
                                                                <button class='iconbtn'><img :src="this.discord" class='iconimage'/>Discord</button><br/>
        <p style='padding-top:80px; padding-left:40px;font-family: Papyrus; font-size:25px;'><strong>Sign up for my monthly Newsletter</strong></p>
        <input type='email' placeholder='Email' class='emailsignup'/>
         <img :src="this.arrow" style='width:40px;height:40px; position:relative; left:50px;; top:50px;border:1px solid #d5a341'/>

  </el-drawer>
        <p style='padding-top:80px; padding-left:40px;font-family: Papyrus; font-size:25px;'><strong>Latest</strong></p>
        <center><hr style='border:.5px solid #d5a341; width:80%'/></center>
  <p style='padding-left:40px;font-family: Papyrus; font-size:18px;'>1. Billion dollar contracts in Connecticut</p>
                                <p style='padding-left:40px;font-family: Papyrus; font-size:18px;'>2. Female Agents making a Fortune</p>
     <p style='padding-left:40px;font-family: Papyrus; font-size:18px;'>3. Buying your first home in New York</p>
          <p style='padding-left:40px;font-family: Papyrus; font-size:18px;'>4. Rental incomes in New York</p>
         <p style='padding-top:80px; padding-left:40px;font-family: Papyrus; font-size:25px;'><strong>What's Trending</strong></p>

        <center><hr style='border:.5px solid #d5a341; width:80%'/></center>

         <p style='padding-top:80px; padding-left:40px;font-family: Papyrus; font-size:23px;'><strong>How much is your home worth in 2023</strong></p>
         <p style='padding-top:80px; padding-left:40px;font-family: Papyrus; font-size:23px;'><strong>Underrated Traits of a successful agent</strong></p>



    </div>
  </div>
</template>

<script>
import pic1 from '../assets/pic1.jpg'
import pic2 from '../assets/pic2.jpg'
import pic3 from '../assets/pic3.jpg'
import pic4 from '../assets/pic4.jpg'
import pic5 from '../assets/pic5.jpg'
import twitter from '../assets/twitter.png'
import facebook from '../assets/facebook.png'
import instagram from '../assets/instagram.png'
import tiktok from '../assets/tiktok.png'
import pinterest from '../assets/pinterest.png'
import linkedin from '../assets/linkedin.png'
import discord from '../assets/discord.png'
import arrow from '../assets/arrow.png'
export default {
    data(){
        return{
            pic:pic1,
            background:pic5,
            drawer:false,
            twitter:twitter,
            facebook:facebook,
            instagram:instagram,
            tiktok:tiktok,
            pinterest:pinterest,
            linkedin:linkedin,
            discord:discord,
            arrow:arrow
        }
    }

}
</script>

<style>
.first{
    display: flex;
}
.follow{
float:right; 
font-size:15; 
padding-right:100px; 
padding-top:20px;
font-family:Papyrus;
}
.follow:hover{
    cursor:pointer;
}
.iconbtn{
    margin:10px;
    background-color: black;
    width:250px;
    height:60px;
    color:#d5a341;
    padding:10px;
    border:.5px solid #d5a341;
    border-radius:3px;
    font-size: 20px;
}
.iconimage{
    width:25px;
    height:25px;
    float:left;
    
   
}
.emailsignup{
    border:0px;
    border-bottom:2px solid #d5a341;
    width:250px;
    position: relative;
    left:40px;
    top:20px;
    height:40px;

}
</style>