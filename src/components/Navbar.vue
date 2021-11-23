<template>
    <div class="navbar">
        <ul class="container nav" >
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <p>DC MERCHANDISE</p>
            </li>
            <li>
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <p>SUBSCRITION</p>
            </li>
            <li>
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <p>COMIC SHOP LOCATOR</p>
            </li>
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <p>DC POWER VISA</p>
            </li>
            
        </ul>

    </div>
  
</template>

<script>
export default {
    name: 'Navbar',


}
</script>

<style scoped lang="scss">
     .navbar{
         width: 100%;
         height: 150px;
         background-color: #0282f9;
         display: flex;
         align-items: center;
        

         .nav{
              justify-content: space-around;
              align-items: center;
         }
        
         li{
             color: #fff;
             list-style: none;
             display: flex;
             align-items: center;
             font-size: 13px;

             img{
                 width: 45px;
                 padding: 5px;
             }
             

         }
     }
    

</style>