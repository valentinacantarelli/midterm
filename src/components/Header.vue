<template>
  <header>
    <img src="../assets/img/logo-sidearea-1.png" alt="logo">
    <nav>
      <ul>
        <li v-for="(el,index) in menu" :key="index">
          <a :href="el.url">{{el.text}}</a></li>
          <i class="fas fa-th"></i>
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
        border-bottom: 3px solid #f0cebe;
      }
    }
  }
  .fa-th{
    padding:2px 0 0 16px;
  }
}
</style>