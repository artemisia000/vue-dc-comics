<template>
     <main>
         <div class="container body">
             <div class="box">

                 <div class="list">
                     <ul>
                         <h2>DC COMICS</h2>
                         <li><a href="">Characters</a></li>
                         <li><a href="">Comics</a></li>
                         <li><a href="">Movies</a></li>
                         <li><a href="">TV</a> </li>
                         <li><a href="">Games</a></li>
                         <li><a href="">Videos</a></li>
                         <li><a href="">News</a></li>
                         <h2>SHOP</h2>
                         <li><a href="">Shop DC</a></li>
                         <li><a href="">Shop DC collectibles</a></li>
                    </ul>
                 </div>

                 <div class="list">
                     <ul>
                         <h2>DC</h2>
                         <li><a href="">Terms of Use</a></li>
                         <li><a href="">Privacy Policy (New)</a></li>
                         <li><a href="">Advertising</a></li>
                         <li><a href="">Jobs</a></li>
                         <li><a href="">Subscriptions</a></li>
                         <li><a href="">CPSC Certificates</a></li>
                         <li><a href="">Ratings</a></li>
                    </ul>
                 </div>

                 <div class="list">
                     <ul>
                         <h2>SITES</h2>
                         <li><a href="">Games</a></li>
                         <li><a href="">DC UNIVERSE INFINITE</a></li>
                         <li><a href="">DC Kids</a></li>
                         <li><a href="">DC Shop</a></li>
                         <li><a href="">MAD Magazine</a></li>
                    
                    </ul>
                 </div>

          </div>

          <div class="logo">
              <img src="../assets/dc-logo-bg.png" alt="">
          </div>


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

   

  
    .list{
        width: 130px;
        text-align: left;
        margin-top: 30px;

        li{
            list-style: none;
        }
        
        a{
            font-size: 12px;
            margin-bottom: 7px;  
            text-decoration: none;
            color:  #7c7c7c;
            &:hover{
                color: #0282f9;
            }

        }
    }

    img{
        height: 300px;
    }
   

    


</style>