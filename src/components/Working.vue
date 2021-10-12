<template>
<div>
  <h2>Working <span><em>process</em> </span> </h2>
  <section class="working">
    <div class="items">
      <div class="roundBg">
        <i class="fas fa-lightbulb"></i>
      </div>
      <h4>First theres an idea</h4>
      <p> Lorem ipsum dolor sit amet</p>
    </div>
    <div class="items">
      <div class="roundBg">
        <i class="far fa-comment"></i>
      </div>
      <h4>Then we talk about</h4>
      <p>Lorem ipsum dolor sit amet</p>
    </div>
    <div class="items">
      <div class="roundBg">
        <i class="fas fa-cloud"></i>
      </div>
      <h4>And we think about</h4>
      <p>Lorem ipsum dolor sit amet</p>
    </div>
    <div class="items">
      <div class="roundBg">
        <i class="fas fa-pencil-alt"></i>
      </div>
      <h4>So we draw along</h4>
      <p>Lorem ipsum dolor sit amet</p>
    </div>
  </section>
</div>
  
</template>

<script>
export default {
    name:"Working"
}
</script>

<style lang="scss" scope>
div{
  font-family: 'Poppins', sans-serif;
  
  h2{
    font-size: 50px;
    text-align: center;
    padding-top: 80px;
    font-weight: 300;

    span{
      font-family: 'Cormorant Upright', serif;
      font-weight: 700;
      font-size: 70px;
    }
  }
  .working{
  width:70%;
  background-image: url(../assets/img/svg-3.svg);
  background-repeat: no-repeat;
  background-position: center;
  display: flex;
  margin-top: 160px;
  margin-bottom:200px;
  justify-content: space-between;
  
  
  .roundBg{
    height:170px;
    width: 170px;
    border-radius: 50%;
    background-color: #faf7f1;
    display:flex;
    align-items: center;
    justify-content: center;
    
    i{
      font-size:43px;
    }
    .fa-lightbulb{
      color: #badac9;
    }
    .fa-comment{
      color: #f8d12d;
    }
    .fa-cloud{
      color:#80465f;
    }
    .fa-pencil-alt{
      color:#eb6950;
    }
  } 
  
  h4{
    font-weight:400;
    text-align: center;
    padding-top:8px;
    } 
   p{
     font-weight: 300;
     font-size: 13px;
     text-align: center;
   } 
}
}
</style>

