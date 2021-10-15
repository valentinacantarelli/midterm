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
        <img src="../assets/img/h-2-slider-img-12.png" alt="foglia" class="bgimg rosa">
        <img src="../assets/img/short-slider-rev-1-img-2.png" alt="foglia" class="bgimg foglia">
        <img src="../assets/img/h-2-slider-img-15.png" alt="hero">
        <img src="../assets/img/h-2-slider-img-16.png" alt="hero">
        <img src="../assets/img/h-2-slider-img-14.png" alt="foglia" class="bgimg viola">
        <img src="../assets/img/short-slider-rev-1-img-6.png" alt="foglia" class="bgimg foglie">
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
  height:310px;
  padding-top:90px;
  background-color: white;

  section{
    display: flex;
    width: 95%;
    justify-content: space-between;

    i{
    background-color: $primaryCol;
    height: 28px;
    width:28px;
    border-radius: 50%;
    color:white;
    margin: 90px 0px;
    text-align: center;
    line-height: 28px;
    transition: 0.3s;
    &:hover{
      background-color: $sndLightGreen;
    }
    }
    .heroLeft{
      width: 37%;
      font-family: 'Poppins', sans-serif;
      font-size:74px;
      font-weight: 300;
      line-height: 68px;

      .alternativeTxt{
        font-family: 'Cormorant Upright', serif;
        font-size:77px;
        font-weight: 700;
      }
      p{
        font-size: 18px;
        line-height: 26px;
        padding: 17px 0;
        color:gray;
      }
      button{
        font-size:14px;
        border: none;
        background-color: white;        
        a{
          padding:16px 30px;
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
        height: 328px;
        position:relative;
      }
      .bgimg{
        position:absolute;
        height:75px;
        bottom:200px;
      }
      .rosa{
          bottom:300px;
          height:45px;
          left:700px;
          opacity:0;
          animation-name:appear;
          animation-duration: 8s;
          animation-iteration-count: infinite;
          @keyframes appear{
          0%{opacity:0;}
          50%{opacity:1;}
          100%{opacity:0;}
        }
        }
      .foglia{
        bottom:510px;
        height: 45px;
        opacity:0;
        animation-name:exs;
        animation-duration:4s;
        animation-iteration-count: infinite;
        animation-timing-function: linear;
        @keyframes exs{
          0%{opacity:0;bottom:510px;}
          25%{opacity:0.5;bottom:520px;}
          50%{opacity:1;bottom:530px;}
          75%{opacity:1;bottom:520px;}
          100%{opacity:0;bottom:510px;}
        }
      }
      .viola{
        bottom:540px;
        right:230px;
        height: 50px;
        opacity:0;
        animation-name:app;
        animation-duration: 5s;
        animation-iteration-count: infinite;
        @keyframes app{
        0%{opacity:0;}
        50%{opacity:1;}
        100%{opacity:0;}
        }
      }
      .foglie{
        bottom:480px;
        height: 45px;
        right:200px;
        opacity:0;
        animation-name:ex;
        animation-duration:6s;
        animation-iteration-count: infinite;
        animation-timing-function: linear;
        @keyframes ex{
          0%{opacity:0;right:200px;}
          25%{opacity:0.5;right:170px;}
          50%{opacity:1;right:185px;}
          75%{opacity:1;right:200px;}
          100%{opacity:0;right:200px;}
        }
      }
    }
  }  
}  

  

</style>