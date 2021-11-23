<template>
    <footer>
        <div class="container nav">
            <div >
                <button class="btn" >SIGN-UP NOW!</button>
            </div>
            <div class="follow">
                   <span>FOLLOW ME</span>
                   <img src="../assets/footer-facebook.png" alt="">
                   <img src="../assets/footer-twitter.png" alt="">
                   <img src="../assets/footer-youtube.png" alt="">
                   <img src="../assets/footer-pinterest.png" alt="">
                    <img src="../assets/footer-periscope.png" alt="">
            </div>

        </div>
    </footer>
     
  
</template>

<script>
export default {
    name: 'Footer'

}
</script>

<style scoped lang="scss" >
    
    footer{
        width: 100%;
        height: 100px;
        background-color: #303030;
        display: flex;
        align-items: center;

        .nav{
            justify-content: space-between;
        }
       
        
    }

    .btn{
        width:120px;
        height: 40px;
        background-color: #303030;
        color: #fff;
        font-weight: 400;
        border: 2px solid #0282f9;

    }

    span{
        color: #0282f9;
        font-size: 20px;
        font-weight: 400;
    }

    img{
        margin: 0 10px;
    }

</style>