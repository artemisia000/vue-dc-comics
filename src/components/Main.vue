<template>
     <main>
         <div class="container body">
             <div class="box">

                 <div class="list">
                     <ul>
                         <h2>DC COMICS</h2>
                         <li>Characters</li>
                         <li>Comics</li>
                         <li>Movies</li>
                         <li>TV</li>
                         <li>Games</li>
                         <li>Videos</li>
                         <li>News</li>
                         <h2>SHOP</h2>
                         <li>Shop DC</li>
                         <li>Shop DC Collectibles</li>
                    </ul>
                 </div>

                 <div class="list">
                     <ul>
                         <h2>DC</h2>
                         <li>Terms of Use</li>
                         <li>Privacy Policy (New)</li>
                         <li>Advertising</li>
                         <li>Jobs</li>
                         <li>Subscriptions</li>
                         <li>CPSC Certificates</li>
                         <li>Ratings</li>
                    </ul>
                 </div>

                 <div class="list">
                     <ul>
                         <h2>SITES</h2>
                         <li>Games</li>
                         <li>DC UNIVERSE INFINITE</li>
                         <li>DC Kids</li>
                         <li>DC Shop</li>
                         <li>MAD Magazine</li>
                    
                    </ul>
                 </div>

             </div>

               <!-- <div class="logo">
                 <img src="../assets/dc-logo-bg.png" alt="">
             </div>
-->

            


         </div>
     </main>
  
</template>

<script>
export default {
    name: 'Main'

}
</script>

<style scoped lang="scss">
    main{
        width: 100%;
        height: 300px;
        background-image: url(../assets/footer-bg.jpg);
        object-fit: cover;

        .box{
            display: flex;
        }

    }

    .body{
        display: flex;
        justify-content: space-between;
    }

    h2{
        color: #fff;
        font-size: 20px;
        margin-bottom: 10px;
    }

    li{
        color: #7c7c7c;
        font-size: 12px;
        list-style: none;
        margin-bottom: 7px;
    }

  
    .list{
        width: 130px;
        text-align: left;
        margin-top: 30px;
    }
   

    


</style>