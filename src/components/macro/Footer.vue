<template>
  <footer>
      <div class="top-footer">
          <div class="container">
                <ul>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../../assets/img/buy-comics-digital-comics.png" alt="esempio">
                            </div>
                            digital comics
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../../assets/img/buy-comics-merchandise.png" alt="esempio">
                            </div>
                            dc merchandise
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../../assets/img/buy-comics-subscriptions.png" alt="esempio">
                            </div>
                            subscription
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../../assets/img/buy-comics-shop-locator.png" alt="esempio">
                            </div>
                            comic shop locator
                        </a>
                    </li>
                    <li>
                        <a href="#">
                            <div class="img-container">
                                <img src="../../assets/img/buy-dc-power-visa.svg" alt="esempio">
                            </div>
                            dc power visa
                        </a>
                    </li>
                </ul>
          </div>
          
      </div>
      <div class="mid-footer">
          <div class="container">
              <div class="mid-container left">
                    <div class="column">
                        <h2>dc comics</h2>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                        <h2>shop</h2>
                        <ul>
                            <li><a href="#">Shop dc</a></li>
                            <li><a href="#">Shop dc collectibles</a></li>
                        </ul>
                    </div>
                    <div class="column">
                        <h2>dc</h2>
                        <ul>
                            <li><a href="#">Terms of use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">jobs</a></li>
                            <li><a href="#">subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CSPC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="column">
                        <h2>sites</h2>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </div>
              </div>
              <div class="mid-container right">
              </div>
          </div>
      </div>
      <div class="bottom-footer">
          <div class="container">
              <div class="left-btm-container">
                  <button>sign-up now!</button>
              </div>
              <div class="right-btm-container">
                  <a href="#">Follow us</a>
                  <img src="../../assets/img/footer-facebook.png" alt="">
                  <img src="../../assets/img/footer-twitter.png" alt="">
                  <img src="../../assets/img/footer-youtube.png" alt="">
                  <img src="../../assets/img/footer-pinterest.png" alt="">
                  <img src="../../assets/img/footer-periscope.png" alt="">
              </div>
          </div>
      </div>
  </footer>
</template>

<script>
export default {
    name: 'Footer'
}
</script>

<style lang="scss" scoped>
   @import '../../assets/style/partials/variables.scss';

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

    .mid-footer{
        background-image: url('../../assets/img/footer-bg.jpg');

        .container{
            display: flex;
            color: white;
            

            .mid-container{
                width: 50%;
                display: flex;

                .column{
                    margin-right: 25px;

                    h2{
                        text-transform: uppercase;
                        padding: 10px 0;
                    }

                    ul{
                        list-style: none;

                        li a{
                            text-decoration: none;
                            color: gray;
                        }
                    
                    }
                }
            }

            .left{
                padding: 50px 0;
            }

            .right{
                background-image: url('../../assets/img/dc-logo-bg.png');
                background-position: center;
                background-repeat: no-repeat;
            }
        }
    }

    .bottom-footer{
        background-color: $secondaryColor;

        .container{
            padding: 30px 0;
            display: flex;
            justify-content: space-between;

            button{
                text-transform: uppercase;
                padding: 10px;
                background-color: $secondaryColor;
                color: white;
                border-color: $mainColor;
                cursor: pointer;
            }

            .right-btm-container{
                width: 35%;
                display: flex;
                align-items: center;
                justify-content: space-around;

                a{
                    text-transform: uppercase;
                    text-decoration: none;
                    font-weight: bold;
                }
            }
        }
    }
</style>