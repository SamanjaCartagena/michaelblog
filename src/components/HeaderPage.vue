<template>
  <div>
    <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="" style='color:#d5a341; font-size:35px;'>
    Michael Levy
    </a>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item">
       Recently Sold
      </a>
       <a class="navbar-item">
       Investments
      </a>
        <a class="navbar-item">
       New Agents
      </a>
       <a class="navbar-item">
       Monday Memo
      </a>
     

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          Selling 
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            Stony Point NY
          </a>
          <a class="navbar-item">
            Jobs
          </a>
          <a class="navbar-item">
            Contact
          </a>
          <hr class="navbar-divider">
          <a class="navbar-item">
            Report an issue
          </a>
        </div>
      </div>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
 
          <a class="button " @click="centerDialogVisible = true" style='background-color:black'>
            Newsletter
          </a>
           <a class="button " style='background-color:black'>
            Calculator
          </a>
        </div>
      </div>
    </div>
  </div>
</nav>
<el-dialog v-model="centerDialogVisible" title="Subscribe for Tips" width="30%" center>
    <span>
      Enter your email to subscribe to our Newsletter
      <br/>
      <input type="email" style="border:0px; border-bottom: 1px solid #d5a341"/>
    </span>
    <template #footer>
      <span class="dialog-footer">
        <el-button @click="centerDialogVisible = false">Cancel</el-button>
        <el-button type="primary" @click="centerDialogVisible = false">
          Confirm
        </el-button>
      </span>
    </template>
  </el-dialog>
  </div>
</template>

<script>
export default {
  data(){
    return{
      centerDialogVisible:false
    }
  }

}
</script>

<style scoped>
.navbar{
    background-color: black;
    color:white;
}
.navbar:hover{
     text-decoration:#d5a341 ;

}
a{
    color:#d5a341;
}
a:hover{
    color:#d5a341;
    text-decoration: #d5a341;
}
.navbar-item{
  background-color: black;
  color:white;
}
.navbar-item :hover{
  text-decoration:#d5a341 ;
  background-color: black;
  color:#d5a341
}
.dialog-footer button:first-child {
  margin-right: 10px;
}

</style>