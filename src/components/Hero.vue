<template>
   <div class="hero">
      <div class="container">
         <div class="label">
            <p>CURRENT SERIES</p>
         </div>
     </div>   
    </div> 
  
</template>

<script>
export default {
    name: 'Hero'

}
</script>

<style scoped lang="scss">

    .hero{
        min-width: 100%;
        max-width: 100%;
        height: 300px;
        background-image: url(../assets/jumbotron.jpg);
        background-repeat: no-repeat;
        background-size: cover;

    }

    .label{
        width: 185px;
        height: 50px;
        text-align: center;
        line-height: 50px;
        background-color: #0282f9;
        color: #fff;
        font-weight: 600;
        font-size: 20px;
        transform: translate(0, +538%);

    }

</style>