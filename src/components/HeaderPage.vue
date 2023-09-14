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
 
          <a class="button " style='background-color:black'>
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
  </div>
</template>

<script>
export default {

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

</style>