<template>
  <div id="app">
    <Header />

    <Goes />

    <Navbar />

    <Main />
    
  </div>
</template>

<script>
import Header from '@/components/Header.vue';
import Goes from '@/components/Goes.vue';
import Navbar from '@/components/Navbar.vue';
import Main from '@/components/Main.vue';

export default {
  name: 'App',
  components: {
    Header,
    Goes,
    Navbar,
    Main,
  }
}


</script>

<style lang="scss">
#app {
  font-family: 'Lato', sans-serif;
  font-family: 'Roboto Condensed', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;

}

.container{
  width: 1000px;
  margin: 0 auto;
  display: flex;

}

</style>
