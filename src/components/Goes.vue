<template>
   <div class="banner ">
       <div class="container">
           <div>
               <a class="goes" href="/"> -->Content goes here</a>
           </div>
       </div>
   </div>


  
</template>

<script>
export default {
    name: 'Goes'

}
</script>

<style scoped lang="scss">
    .banner{
        width: 100%;
        height: 100px;
        background-color: #000;
        display: flex;
        align-items: center;
    }

    .goes{
        color: #fff;
        font-size: 25px;
        font-weight: 600;
    }
    
    a{
        justify-content: flex-start;
        text-decoration: none;
    }


</style>