<template>
  <footer>
    <section class="menu">
      <div>
        <img src="../assets/img/logo-sidearea-1.png" alt="logo">
        <p>Let's Get Creative</p>
      </div>
      <div>
        <p>maree.qode@gmail.com</p> 
        <p>+44645 321 789</p>
      </div>
      <div>
        <p>Avenue d'Auderghem 10</p> 
        <p>1040 Brussels, Belgium</p> 
      </div>
      <div>
        <p>Stay in touch with us</p> 
        <p class="social">
          <a href="#"><i class="fab fa-twitter"></i></a>
          <a href="#"><i class="fab fa-pinterest-p"></i></a>
          <a href="#"><i class="fab fa-facebook-f"></i></a>
          <a href="#"><i class="fab fa-linkedin-in"></i></a>
        </p> 
      </div>
    </section>
  </footer>
</template>

<script>
export default {
    name:"Footer",
    
}
</script>

<style  lang="scss" scope>
footer{
  background-color: #c0e1cf;
  .menu{
    padding:60px 0 80px 0;
    display:flex;
    justify-content: space-between;
    p{
      padding-top:10px;
      font-size: 15px;
      font-weight: 300;
    }
    .social{
      display:flex;
      justify-content: space-between;
      font-size:18px;
    }
  }
}
</style>