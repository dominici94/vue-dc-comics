<template>
  <footer>
      <div class="top-footer">
          <div class="container">
                <ul>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../assets/img/buy-comics-digital-comics.png" alt="esempio">
                            </div>
                            digital comics
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../assets/img/buy-comics-merchandise.png" alt="esempio">
                            </div>
                            dc merchandise
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../assets/img/buy-comics-subscriptions.png" alt="esempio">
                            </div>
                            subscription
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../assets/img/buy-comics-shop-locator.png" alt="esempio">
                            </div>
                            comic shop locator
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../assets/img/buy-dc-power-visa.svg" alt="esempio">
                            </div>
                            dc power visa
                        </a>
                    </li>
                </ul>
          </div>
          
      </div>
      <div class="mid-footer"></div>
      <div class="bottom-footer"></div>
  </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
   @import '../assets/style/partials/variables.scss';

    .top-footer{
        background-color: $mainColor;
        padding: 50px;

        ul{
            display: flex;
            justify-content: space-around;
            list-style: none;

            li{
                margin: 0 10px;

                a{
                    color: white;
                    text-decoration: none;
                    display: flex;
                    align-items: center;
                    text-transform: uppercase;

                    .img-container{
                        height: 50px;

                        img{
                            height: 100%;
                            margin-right: 10px;
                        }
                    }
                }
            }

            
        }
        
    }
</style>