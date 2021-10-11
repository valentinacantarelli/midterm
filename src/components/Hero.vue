<template>
  <div class="hero">
    <section>
      <i class="fas fa-chevron-left"></i>
      <div class="heroLeft"><span>  Devotion that never</span> <span class="alternativeTxt"><em>ends</em></span>
      <p>Lorem ipsum dmet,  uptatibus pro sint aut dolorum, aliquid 
        conquatur sit accusamus doloribus.</p>
        <button><a href="#"> READ MORE</a></button>
      </div>
      <div class="heroRight">
        <img src="../assets/img/h-2-slider-img-13.png" alt="foglia" class="bgimg">
        <img src="../assets/img/h-2-slider-img-15.png" alt="hero">
        <img src="../assets/img/h-2-slider-img-16.png" alt="hero">
        <img src="../assets/img/h-2-slider-img-17.png" alt="foglia" class="bgimg">
      </div>
      <i class="fas fa-chevron-right"></i>
    </section>
  </div>
</template>

<script>
export default {
    name:"Hero"
}
</script>

<style  lang="scss" scope>
@import '../assets/style/variables';
.hero{
  width:100%;
  height:200px;
  padding-top:80px;

  section{
    display: flex;
    width: 95%;
    justify-content: space-between;

    i{
    background-color: $primaryCol;
    height: 20px;
    width:20px;
    border-radius: 50%;
    color:white;
    margin: 90px 0px;
    text-align: center;
    line-height: 20px;
    }

    .heroLeft{
      width: 30%;
      font-family: 'Poppins', sans-serif;
      font-size:45px;
      font-weight: 300;
      line-height: 50px;

      .alternativeTxt{
        font-family: 'Cormorant Upright', serif;
        font-size:65px;
        font-weight: 700;
      }
      p{
        font-size: 13px;
        line-height: 16px;
        padding: 17px 0;
      }
      button{
        font-size:12px;
        border: 3px solid $primaryCol;
        padding: 8px 13px;
        background-color: white;
        font-weight: 700;
      }
    }
    .heroRight{
      width:39%;

      img{
        height: 250px;
      }
      .bgimg{
        height:55px;
      }
    }
  }  
}  

  

</style>