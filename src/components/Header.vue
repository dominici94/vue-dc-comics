<template>
  <header>
      <div class="container">
            <div class="logo">
                <img src="../assets/img/dc-logo.png" alt="logo dc">
            </div>
            
            <nav>
                <ul>
                    <li><a class="active" href="#">Characters</a></li>
                    <li><a href="#">Comics</a></li>
                    <li><a href="#">Movies</a></li>
                    <li><a href="#">Tv</a></li>
                    <li><a href="#">Games</a></li>
                    <li><a href="#">Collectibles</a></li>
                    <li><a href="#">Videos</a></li>
                    <li><a href="#">Fans</a></li>
                    <li><a href="#">News</a></li>
                    <li><a href="#">Shop</a></li>
                </ul>
            </nav>
      </div>
      
      
  </header>
</template>

<script>
export default {
    name: 'Header',
}
</script>

<style lang="scss" scoped>
@import '../assets/style/partials/variables.scss';

    header{
        height: 100px;
        padding: 10px;
        margin-bottom: 30px;

        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;

            ul{
                list-style: none;
                    li{
                        display: inline-block;
                        padding: 5px;
                        margin: 0 10px;

                        a{
                            color: black;
                            text-decoration: none;
                            text-transform: uppercase;
                        }

                        .active{
                        color: $mainColor;
                        border-bottom: 2px solid $mainColor;
                    }
                    }
                    
                
            }
        }
    }


</style>