<template>
  <header>
      <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="logo dc">
            </div>
            
            <nav>
                <ul>
                    <li v-for="(link,index) in links" :key="index"><a :class="{active: link.current}" :href="link.url">{{link.text}}</a></li>
                </ul>
            </nav>
      </div>
      
      
  </header>
</template>

<script>
export default {
    name: 'Header',
    data(){
        return{
            links : [
                {
                    text: 'Characters',
                    url: '#',
                    current: true
                },
                {
                    text: 'Comics',
                    url: '#',
                    current: false
                },
                {
                    text: 'Movies',
                    url: '#',
                    current: false
                },
                {
                    text: 'Tv',
                    url: '#',
                    current: false
                },
                {
                    text: 'Games',
                    url: '#',
                    current: false
                },
                {
                    text: 'Collectibles',
                    url: '#',
                    current: false
                },
                {
                    text: 'Videos',
                    url: '#',
                    current: false
                },
                {
                    text: 'Fans',
                    url: '#',
                    current: false
                },
                {
                    text: 'News',
                    url: '#',
                    current: false
                },
                {
                    text: 'Shop',
                    url: '#',
                    current: false
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';

    header{
        // height: 100px;
        // padding: 10px;
        // margin-bottom: 30px;

        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;

            nav{
                line-height: 120px;
            }

            ul{
                list-style: none;
                    li{
                        display: inline-block;
                        padding: 0 5px;
                        margin: 0 10px;

                        a{
                            color: black;
                            text-decoration: none;
                            text-transform: uppercase;
                            display: inline-block;
                        }

                        .active{
                        color: $mainColor;
                        border-bottom: 5px solid $mainColor;
                        }
                    }
                    
                
            }
        }
    }


</style>