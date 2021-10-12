<template>
  <section class="blog">
    <div class="post">
        <img src="../assets/img/h-2-blog-img-1.jpg" alt="post">
        <h3>This way, loves: a detailed guide through new design</h3>
        <p><em>  By Emily Fields</em></p>
    </div>
    <div class="post">
        <img src="../assets/img/h-2-blog-img-2.jpg" alt="post">
        <h3>Try to give people a different way of looking art</h3>
        <p><em>  By Emily Fields</em></p>
    </div>
    <div class="post">
        <img src="../assets/img/h-2-blog-img-3.jpg" alt="post">
        <h3>Introduce Richard Laperrière of those amazing features</h3>
        <p><em>  By Emily Fields</em></p>
    </div>
  </section>
</template>

<script>
export default {
    name:"Articles"
}
</script>

<style lang="scss" scope>
.blog{
    display:flex;
    margin-top:130px;
    justify-items: space-between;
    .post{
        width: calc(100% / 3);
        img{
            width:380px;
        }
        h3{
            font-weight: 400;
            padding:15px 5px;
        }
        p{
            font-family: 'Cormorant Upright', serif; 
            font-size: 16px;
            padding:0 5px;
            font-weight: 500;
            margin-bottom: 80px;
        }
    }
}
</style>