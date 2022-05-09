<template>
    <footer>
        <div class="container nav">
            <div >
                <button class="btn" >SIGN-UP NOW!</button>
            </div>
            <div class="follow">
                   <span>FOLLOW US</span>
                    <a href="">
                       <img src="../assets/footer-facebook.png" alt="">
                    </a>
                    <a href="">
                       <img src="../assets/footer-twitter.png" alt="">
                    </a>
                    <a href="">
                       <img src="../assets/footer-youtube.png" alt="">
                    </a>
                    <a href="">
                       <img src="../assets/footer-pinterest.png" alt="">
                    </a>
                    <a href="">
                        <img src="../assets/footer-periscope.png" alt="">
                    </a>
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

            .follow{
                display: flex;
                align-items: center;
            }
        }        
    }

    .btn{
        width:140px;
        height: 45px;
        background-color: #303030;
        color: #fff;
        font-weight: 400;
        border: 2px solid #0282f9;
        cursor: pointer;
        &:hover{
            background-color: #0282f9;
            transition: 2s;
        }
    }

    span{
        color: #0282f9;
        font-size: 20px;
        font-weight: 600;
        margin-right: 20px;
    }
    a{
        margin: 0 10px;
        &:hover{
            color:#4d4d4d ;
            transform: scale(0.8);
        }
    }

</style>