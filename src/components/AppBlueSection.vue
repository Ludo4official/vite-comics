<script>

    export default {

        name:'AppBlueSection',
        data() {

            return {
                
            };

        },

};

</script>

<template>

    <div class="blueSection">

        <div class="bluCnt">
            <div class="cards">
                <div class="cardLogo">
                    <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                </div>
                <div class="cardText">
                    digital comics
                </div>
            </div>
            <div class="cards">
                <div class="cardLogo">
                    <img src="../assets/img/buy-comics-merchandise.png" alt="">
                </div>
                <div class="cardText">
                    dc merchandise
                </div>
            </div>
            <div class="cards">
                <div class="cardLogo">
                    <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                </div>
                <div class="cardText">
                    subscription
                </div>
            </div>
            <div class="cards">
                <div class="cardLogo">
                    <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                </div>
                <div class="cardText">
                    comic shop locator
                </div>
            </div>
            <div class="cards">
                <div class="cardLogo">
                    <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                </div>
                <div class="cardText">
                    dc power visa
                </div>
            </div>
        </div>

    </div>

</template>

<style lang="scss" scoped>

    .blueSection {
        height: 120px;
        background-color: #0c7cec;

        .bluCnt {
            width: 70%;
            height: 100%;
            margin: 0 auto;
            display: flex;

            .cards {
                width: calc(100% / 5);
                height: 100%;
                display: flex;

                .cardLogo {
                    width: 50%;
                    height: 100%;
                    display: flex;
                    align-items: center;
                    justify-content: center;

                    img {
                        width: 50px;
                    }
                }

                .cardText {
                    width: 50%;
                    height: 100%;
                    display: flex;
                    align-items: center;
                    justify-content: center;
                    text-transform: uppercase;
                    font-weight: bold;
                    font-size: 0.9rem;
                    color: white;

                    &:hover {
                        cursor: pointer;
                        color: black;
                    }
                }
            }
        }
    }

</style>