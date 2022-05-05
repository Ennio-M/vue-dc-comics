<template>
    <footer>
        <section class="footer-top">
            <div class="container">
                <section class="lists">
                    <div class="links">
                        <h4>Dc Comics</h4>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>
                        </ul>
                        <h4>Shop</h4>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>
                        </ul>
                    </div>
                    <div class="links">
                        <h4>Dc</h4>
                        <ul>
                            <li><a href="#">Terms Of Use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>
                            <li><a href="#">Ad Choices</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>
                            <li><a href="#">Subscriptions</a></li>
                            <li><a href="#">Talent Workshops</a></li>
                            <li><a href="#">CPSC Certificates</a></li>
                            <li><a href="#">Ratings</a></li>
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Us</a></li>
                        </ul>
                    </div>
                    <div class="links">
                        <h4>Sites</h4>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MAD Magazine</a></li>
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>
                        </ul>
                    </div>
                </section>
                <div class="bg-logo">
                </div>
            </div>
        </section>
        <section class="footer-bottom">
            <div class="container">
                <div class="signup">
                    <button>Sign-up now!</button>
                </div>
                <section class="socials">
                    <h4>Follow us</h4>
                    <img src="../assets/imgs/footer-facebook.png" alt="Facebook Logo">
                    <img src="../assets/imgs/footer-twitter.png" alt="Twitter Logo">
                    <img src="../assets/imgs/footer-youtube.png" alt="YouTube Logo">
                    <img src="../assets/imgs/footer-pinterest.png" alt="Pinterest Logo">
                    <img src="../assets/imgs/footer-periscope.png" alt="Periscope Logo">
                </section>
            </div>
        </section>
    </footer>
</template>

<script>
export default {
    name: 'AppFooter'    
}
</script>

<style lang="scss" scoped>
    @import '../style/variables.scss';
    @import '../style/general.scss';

    // footer top
    .footer-top{
        height: 300px;
        background-image: url(../assets/imgs/footer-bg.jpg);

        .container{
            display: flex;
            justify-content: space-between;

            .bg-logo{
                width: 500px;
                background-image: url(../assets/imgs/dc-logo-bg.png);
                background-size: cover;
                background-position: center;
            }
        }
    }
    .lists{
        display: flex;
        align-items: flex-start;
    }
    .links{
        margin: 20px 20px 0 0;

        h4{
            text-transform: uppercase;
            color: $white;
            padding: 12px 0 6px;
        }

        li a{
            color: $gray;
            font-size: .8em;
            padding: 2px 0;
            text-decoration: none;
        }
    }

    // footer bottom
    .footer-bottom{
        height: 80px;
        background-color: $dark;

        .container{
            display: flex;
            justify-content: space-between;
            align-items: center;
        }
    }
    .signup button{
        text-transform: uppercase;
        background-color: $dark;
        color: $white;
        border-color: $dc-blue;
        border-style: solid;
        padding: 12px;
        cursor: pointer;
    }
    .socials{
        width: 350px;
        display: flex;
        justify-content: space-around;
        align-items: center;
        h4{
            text-transform: uppercase;
            color: $dc-blue;
        }
        *{
            cursor: pointer;
        }
    }
</style>