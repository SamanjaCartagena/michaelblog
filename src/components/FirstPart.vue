<template>
  <div class="first">
    <div style="background-color:black; width:75%;
    height:500px;">
    <img :src="this.background" style="width:100%; height:700px;"  />
    </div>
    <div style=' width:30%; height:700px;'>
        <p style='float:right; font-size:30px; padding-right:100px; font-family:Papyrus'>Follow</p>
        <p style='padding-top:80px; padding-left:40px;font-family: Papyrus; font-size:25px;'>Latest</p>
        <center><hr style='border:.5px solid #d5a341; width:80%'/></center>
  <p style='padding-left:40px;font-family: Papyrus; font-size:18px;'>1. Billion dollar contracts in Connecticut</p>
                                <p style='padding-left:40px;font-family: Papyrus; font-size:18px;'>2. Female Agents making a Fortune</p>
     <p style='padding-left:40px;font-family: Papyrus; font-size:18px;'>3. Buying your first home</p>
          <p style='padding-left:40px;font-family: Papyrus; font-size:18px;'>4. Rental incomes in New York</p>
         <p style='padding-top:80px; padding-left:40px;font-family: Papyrus; font-size:25px;'>What's Trending</p>

        <center><hr style='border:.5px solid #d5a341; width:80%'/></center>



    </div>
  </div>
</template>

<script>
import pic1 from '../assets/pic1.jpg'
import pic2 from '../assets/pic2.jpg'
import pic3 from '../assets/pic3.jpg'
import pic4 from '../assets/pic4.jpg'
import pic5 from '../assets/pic5.jpg'
export default {
    data(){
        return{
            pic:pic1,
            background:pic5
        }
    }

}
</script>

<style>
.first{
    display: flex;
}
</style>