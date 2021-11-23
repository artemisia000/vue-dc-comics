<template>
   <header class="container" >
        <div>
            <img src="../assets/dc-logo.png" alt="">
        </div>
        <div>
            <ul>
                <li>GAMES</li>
                <li>COMICS</li>
                <li>MOVIES</li>
                <li>TV</li>
                <li>GAMES</li>
                <li>COLLECTIBLES</li>
                <li>VIDEOS</li>
                <li>FANS</li>
                <li>NEWS</li>
                <li>SHOP</li>

            </ul>
        </div>
   </header>
  
</template>

<script>
export default {
    name: 'header',
    data() {

        return {
            
        }

    }

}
</script>

<style scoped lang="scss">

    header{
        height: 100px;
        justify-content: space-between;
        align-items: center;
    }
     ul{
         display: flex;
         list-style: none;
         
        

     }


</style>