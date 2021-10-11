<template>
  <header>
    <img src="../assets/img/logo-sidearea-1.png" alt="logo">
    <nav>
      <ul>
        <li v-for="(el,index) in menu" :key="index">
          <a :href="el.url">{{el.text}}</a></li>
          <span><img src="../assets/img/svg-1.svg" alt=""></span>
      </ul>
      
    </nav>
  </header>
</template>

<script>
export default {
    name:"Header",
    data(){
      return{
        menu:[
          {
            text:"HOME",
            url:"#",
          },
          {
            text:"PAGES",
            url:"#",
          },
          {
            text:"PORTFOLIO",
            url:"#",
          },
          {
            text:"BLOG",
            url:"#",
          },
          {
            text:"SHOP",
            url:"#",
          },
          {
            text:"ELEMENTS",
            url:"#",
          },
        ]
      }
    },
}
</script>

<style  lang="scss" scope>
@import '../assets/style/variables';
header{
  display: flex;
  width:100%;
  padding:20px;
  justify-content: space-between;
  font-family: 'Poppins', sans-serif;

  img{
    height: 20px;
  }

  ul{
    display: flex;
    margin-right:18px;

    li{
      padding:0px 15px;
      font-size: 13px;
      font-weight:500;

      a:hover{
        border-bottom: 3px solid $primaryCol;
      }
    }
  }
  span{
    padding-left:16px;
    
    img{
      height:15px;
    }
  }
}
</style>