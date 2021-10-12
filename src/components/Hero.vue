<template>
  <div class="hero">
    <section>
      <a href="#"><i class="fas fa-chevron-left"></i></a>
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
      <a href="#"><i class="fas fa-chevron-right"></i></a>
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
  height:290px;
  padding-top:90px;
  background-color: white;

  section{
    display: flex;
    width: 95%;
    justify-content: space-between;

    i{
    background-color: $primaryCol;
    height: 25px;
    width:25px;
    border-radius: 50%;
    color:white;
    margin: 90px 0px;
    text-align: center;
    line-height: 25px;
    }
    .heroLeft{
      width: 33%;
      font-family: 'Poppins', sans-serif;
      font-size:67px;
      font-weight: 300;
      line-height: 65px;

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
        font-size:14px;
        border: none;
        background-color: white;
        padding:10px 15px;
        
        a{
          padding:10px 15px;
          border: 3px solid $primaryCol;
          transition: 0.3s;
          &:hover{
            color: white;
            background-color: $primaryCol;
          }
        }
      }
    }
    .heroRight{

      img{
        height: 320px;
      }
      .bgimg{
        height:75px;
      }
    }
  }  
}  

  

</style>