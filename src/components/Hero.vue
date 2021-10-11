<template>
  <div class="hero">
    <section>
      <div class="heroLeft"><span>  Devotion that never</span> <span class="alternativeTxt"><em>ends</em></span>
      <p>Lorem ipsum dmet,  uptatibus pro sint aut dolorum, aliquid 
        conquatur sit accusamus doloribus.</p>
        <button>READ MORE</button>
      </div>
      <div class="heroRight"></div>
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
  height :200px;
  padding-top:80px;

  .heroLeft{
    width: 31%;
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
}
</style>