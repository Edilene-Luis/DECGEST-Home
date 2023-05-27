<template>
    
    <div>
  <b-navbar class="back " toggleable="lg" type="dark" variant="info">
    <b-navbar-brand href="#" style="width: 230px; height: 100px;"><img src="../static/images/logoteste.jpg" alt="Logo-DECgest" class="logo1" ></b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"><svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path fill="#2fe821" d="M20 11H4c-.6 0-1 .4-1 1s.4 1 1 1h16c.6 0 1-.4 1-1s-.4-1-1-1zM4 8h16c.6 0 1-.4 1-1s-.4-1-1-1H4c-.6 0-1 .4-1 1s.4 1 1 1zm16 8H4c-.6 0-1 .4-1 1s.4 1 1 1h16c.6 0 1-.4 1-1s-.4-1-1-1z"/></svg> </b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="centro">
        <b-nav-item href="#">ATIVOS</b-nav-item>
        <b-nav-item href="#" >APRENDIZADO</b-nav-item>
        <b-nav-item href="#" >SIMULAÇÃO</b-nav-item>  
    </b-navbar-nav>

    </b-collapse>
  </b-navbar>
</div>

</template>

<style scoped>
 
 .navbar-collapse{
  justify-content: right;
  margin-right: 50px;
  
 }

  .bg-info {
    background-color: #fff !important;
}

.navbar-dark .navbar-brand {
    padding-left: 30px !important;
    color: black !important;
    

}

.navbar-dark .navbar-nav .nav-link {
    color: black !important;
}

.navbar {
    position: relative;
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: space-between;
    padding: .1rem 1rem;
    text-align: center;
    transition: all .5s;
    
    
}

.nav-item:hover{

  border-bottom:1px solid #3cb748;
  transition: all 2s;
  

}

.logo1{
    width: 80%;
     height: 60%; 
     margin-top: 11px;
  }


@media (max-width: 990px){



  .nav-item:nth-child(1){
    border-bottom: 1px solid black;
  }

  .navbar-collapse{
    transition: all 2s;
  }

  .navbar-toggler{
    border: 1px solid #3cb748 !important;
  }

  .logo1{
    width: 80%;
    height: 60%;
    margin-top: 20px;
    margin-left: 60px;
  }

  

 

}




</style>

<script>
export default {

}
</script>

<style>

</style>