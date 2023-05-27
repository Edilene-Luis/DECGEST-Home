<template>
  <div class="banner vh-100 vw-100">

  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
.banner{
    position: relative;
}
.banner::before{
    content: "";
    position: absolute;
    top: 0;
    left: 0;    
    height: 80%;
    width: 100%;
    background: url(/images/banner-dinheiro.jpg) no-repeat center;
    background-size: cover; 
}
</style>