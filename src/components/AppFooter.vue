<script>

import AppBlueSection from './AppBlueSection.vue';

    export default {

        name:'AppFooter',
        data() {

            return {
                
            };

        },

        components: {

            AppBlueSection,
        },

};

</script>

<template>

    <AppBlueSection/>

    <div class="footer">

        <div class="footerCnt">

            <div class="infos">
                <div class="info">
                    <div class="info-1-1">
                        <h3>dc comics</h3>
                        <ul>
                            <li>Characters</li>
                            <li>Comics</li>
                            <li>Movies</li>
                            <li>Tv</li>
                            <li>Games</li>
                            <li>Videos</li>
                            <li>News</li>
                        </ul>
                    </div>
                    <div class="info-1-2">
                        <h3>shop</h3>
                        <ul>
                            <li>Shop DC</li>
                            <li>Shop DC Collectibles</li>
                        </ul>
                    </div>
                </div>
                <div class="info">
                    <h3>dc</h3>
                    <ul>
                        <li>Terms Of Use</li>
                        <li>Privacy policy (new)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>Talent Workshops</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </ul>
                </div>
                <div class="info">
                    <h3>sites</h3>
                    <ul>
                        <li>DC</li>
                        <li>MAD Magazine</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power Visa</li>
                    </ul>
                </div>
            </div>

            <div class="DC">
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </div>

        </div>

    </div>

    <div class="ultCnt">
        <div class="signUp">
            <div class="sign">
                Sign-Up Now
            </div>
            <div class="socials">
                <div class="follow">Follow Us!</div>
                <img src="../assets/img/footer-facebook.png" alt="">
                <img src="../assets/img/footer-periscope.png" alt="">
                <img src="../assets/img/footer-pinterest.png" alt="">
                <img src="../assets/img/footer-twitter.png" alt="">
                <img src="../assets/img/footer-youtube.png" alt="">
            </div>
        </div>
    </div>
    

</template>

<style lang="scss" scoped>

    .footer {
        width: 100%;
        min-height: calc(100% - 420px);
        background-image: url(../assets/img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        opacity: 0.9;
        

        .footerCnt {
            width: 70%;
            height: 100%;
            margin: 0 auto;
            display: flex;
        

            .infos {
                width: 50%;
                height: 100%;
                display: flex;

                .info {
                    width: calc(100% / 3);
                    height: 100%;
                    padding-top: 20px;
                    font-size: 0.8rem;

                    h3 {
                        color: white;
                        text-transform: uppercase;
                        font-size: 1.5rem;
                    }

                    ul {
                        list-style: none;

                        li {
                            margin-top: 10px;
                            color: white;
                            opacity: 0.6;
                        }

                    }
                }

                    .info-1-2 {
                        margin-top: 40px;
                    }
            }
        }
    }

            .DC {
                width: 50%;
                height: 100%;
                opacity: 0.5;

                img {
                    width: 70%;
                }
            }

    .ultCnt {
        height: 100px;
        background-color: black;
         
        .signUp {
            width: 70%;
            margin: 0 auto;
            display: flex;
            justify-content: space-between;
            align-items: center;
            height: 100%;

            .sign {
                color: white;
                border: 2px solid #0c7cec;
                padding: 10px 20px;

                &:hover {
                    cursor: pointer;
                    background-color: #0c7cec;
                    color: black;
                    font-weight: bold;
                }
            }

            .socials {
                display: flex;
                align-items: center;

                .follow {
                    color: #0c7cec;
                    font-weight: bold;
                    margin-right: 20px;
                    text-transform: uppercase;

                    &:hover {
                        cursor: pointer;
                        color: black;
                        background-color: #0c7cec;
                        padding: 10px 20px;
                    }
                }

                img {
                    padding: 10px;

                    &:hover {
                        cursor: pointer;
                    }
                }
            }
        
        }
    }

</style>