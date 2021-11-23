<template>
    <div class="navbar">
        <ul class="container" >
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </li>
            <li>
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <p>DIGITAL COMICS</p>
            </li>
        </ul>


    </div>
  
</template>

<script>
export default {
    name: 'Navbar'

}
</script>

<style scoped lang="scss">
     .navbar{
         width: 100%;
         height: 150px;
         background-color: #0282f9;

         li{
             color: #fff;
             list-style: none;
             display: flex;
             align-items: center;

             img{
                 width: 40px;
             }
             

         }
     }
    

</style>