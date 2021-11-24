<template>
   <header class="container" >
        <div>
            <img src="../assets/dc-logo.png" alt="">
        </div>
        <div>
            <ul>
                <li v-for="(link ,index) in navLink" :key="`link-${index}`" >
                    <a :class="{active: link.current}" 
                       :href="link.url"> 
                       {{ link.text }} 
                    </a>
                </li>
            
            </ul>
        </div>
   </header>
  
</template>

<script>
export default {
    name: 'Header',

     data() {

        return {
            navLink: [
                {
                    text: 'GAMES',
                    url: '/GAMES',
                    current: false,
                },
                               {
                    text: 'COMICS',
                    url: '/COMICS',
                    current: false,
                },
                               {
                    text: 'MOVIES',
                    url: '/MOVIES',
                    current: false,
                },
                               {
                    text: 'TV',
                    url: '/TV',
                    current: false,
                },
                               {
                    text: 'GAMES',
                    url: '/',
                    current: false,
                },
                               {
                    text: 'COLLECTIBLES',
                    url: '/',
                    current: false,
                },
                               {
                    text: 'VIDEOS',
                    url: '/',
                    current: false,
                },
                               {
                    text: 'FANS',
                    url: '/',
                    current: false,
                },
                               {
                    text: 'NEWS',
                    url: '/',
                    current: false,
                },
                               {
                    text: 'SHOP',
                    url: '/',
                    current: false,
                },

            ],

        };

    },

};

</script>

<style scoped lang="scss">

    header{
        height: 100px;
        justify-content: space-between;
        align-items: center;

        img{
            width: 60px;
        }
    }
     ul{
        
         display: flex;
         list-style: none;
         font-size: 12px;

         li{
             height: 100px;
             display: flex;
             align-items: center;
             &:hover{
                 border-bottom: 4px solid #0282f9;
                 transition:  0.5s ease;
                 color: #0282f9;
             }
         }

      
         a{
             color: #464646;
             padding: 0 1rem;
             text-decoration: none;
             font-weight: 600;
             &.active,
             &:hover{
                color: #0282f9;
             }
             

         }
         
        

     }


</style>