<template>
    <div class="message">
        <section >
            <h2>Want to work with us? Send us <span><em>a message!</em></span></h2>
            <p> Lorem ipsum, dolor sit amet consectetur adipisicing elit. Hic modi debitis voluptas quod veritatis, aperiam ipsam deserunt e
                arum aliquid ratione consequatur nemo, natus doloribus rerum delectus facere ad nisi odit.</p>   
            <button><a href="#">CONTACT</a></button>    
        </section>
    </div>
</template>

<script>
export default {
    name:"Message"
}
</script>

<style lang="scss" scope>
.message{
    background-image:url(../assets/img/h-2-background-1.jpg);
    height:100%;
    width: 100%;
    background-position: center;
    background-size: cover;
    
    section{
        padding:45px 0;
        text-align: center;
        h2{
            font-size: 55px;
            padding-bottom: 30px;
        }
        p{
            font-weight: 300;
            font-size: 17px;
            padding-bottom: 40px;
        }
        button{
            background-color: #d8f0e3; 
            border: none;
            padding:20px 42px;
            margin-bottom:50px;
            transition: 0.3s;
            &:hover{
                background-color: #f3d0c7;
                
            }
            a{
                padding:15px;
                transition: 0.3s;
                &:hover{
                    color:white;
                }
            }
        }
    }
}
</style>