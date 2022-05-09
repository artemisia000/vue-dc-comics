<template>
    <div class="navbar">
        <ul class="container nav" >
            <li>
                <a href="/">
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                </a>  
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <a href="/">
                    <img src="../assets/buy-comics-merchandise.png" alt="">
                </a>
                <p>DC MERCHANDISE</p>
            </li>
            <li>
                <a href="/">
                    <img src="../assets/buy-comics-subscriptions.png" alt="">
                </a>
                <p>SUBSCRITION</p>
            </li>
            <li>
                <a href="/">
                    <img src="../assets/buy-comics-shop-locator.png" alt="">
                </a>
                <p>COMIC SHOP LOCATOR</p>
            </li>
            <li>
                <a href="/">
                    <img src="../assets/buy-comics-digital-comics.png" alt="">
                </a>
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
             img {
                 width: 50px;
                 height: 58px;
                 padding: 5px;                
             }           
         }
     }
</style>