<template>
    <div class="footer_container">
        <div class="footer_store_buy">
            <ul>
                <li><img src="@/assets/buy-comics-digital-comics.png" alt=""><span>COMICS</span> </li>
                <li><img src="@/assets/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span></li>
                <li><img src="@/assets/buy-comics-subscriptions.png" alt=""><span>SUBSCRIPTION</span></li>
                <li><img src="@/assets/buy-comics-shop-locator.png" alt=""><span>COMIC SHOP LOCATOR</span></li>
                <li><img src="@/assets/buy-dc-power-visa.svg" alt=""><span>DC POWER VISA</span></li>
            </ul>

        </div>
        <div class="footer_dc_links">
            <div class="footer_links_left">
                <div class="links_left">
                    <ul><span>DC COMICS</span>
                        <li><a href="">Characters</a> </li>
                        <li><a href="">Comics</a> </li>
                        <li><a href="">Movies</a> </li>
                        <li><a href="">TV</a> </li>
                        <li><a href="">Games</a> </li>
                        <li><a href="">Videos</a> </li>
                        <li><a href="">News</a> </li>
                    </ul>
                    <ul><span>SHOP</span>
                        <li><a href="">Shop DC</a> </li>
                        <li><a href="">Shop DC Collectibles</a> </li>
                    </ul>

                </div>
                <div class="links_middle">
                    <ul><span>DC</span>
                        <li><a href=""> Terms Of Use</a></li>
                        <li><a href=""> Privacy policy (New)</a></li>
                        <li><a href=""> Ad Choices</a></li>
                        <li><a href=""> Advertising</a></li>
                        <li><a href=""> Jobs</a></li>
                        <li><a href=""> Subscriptions</a></li>
                        <li><a href=""> Talent Workshops</a></li>
                        <li><a href=""> CPSC Certificates</a></li>
                        <li><a href=""> Ratings</a></li>
                        <li><a href=""> Shop Help</a></li>
                        <li><a href=""> Contact Us</a></li>

                    </ul>

                </div>
                <div class="links_right">
                    <ul><span>SITES</span>
                        <li><a href=""> DC</a></li>
                        <li><a href=""> MAD Magazine</a></li>
                        <li><a href=""> DC Kids</a></li>
                        <li><a href=""> DC Universe</a></li>
                        <li><a href=""> DC Power Visa</a></li>
                    </ul>

                </div>
            </div>
            <div class="footer_logo_right">
                
            </div>

        </div>
        <div class="signup_n_socials">

        </div>
    </div>
    
</template>

<script>
    export default{
        name: 'HomeFooter'
    }
</script>

<style lang="scss" scoped>
    .footer_store_buy{
        height: 160px;
        background-color: #0282F9;
        display: flex;
        justify-content: center;
        
        ul{
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
        li{
            color: white;
            padding: 30px;
            display: flex;
            align-items: center;
            img{
                // width: 60px;
                max-height: 70px;
            }
            span{
                padding: 10px;
            }
        }
    }
    .footer_dc_links{
        height: 370px;
        background-image: url(@/assets/footer-bg.jpg);
        background-size: contain;
        display: flex;
        justify-content: space-between;
        align-items: center;
        .footer_links_left{
            display: flex;
            flex-direction: row;
        }
        ul{
            text-align: left;
        }
        
        span{
            color: white;
            padding-top: 16px;
            padding-bottom: 16px;
            
        }
        li{
            color: lightgray;
            text-align: left;
            padding: 5px 0px;
        }
        .links_middle{
            padding-inline: 35px;
        }
    }
    .footer_logo_right{
        background-image: url(@/assets/dc-logo-bg.png);
        height: 100%;
        width: 40%;
        background-repeat: no-repeat;
        background-position: center;
    }
    .signup_n_socials{
        background-color: #303030;
        height: 108px;
    }

</style>