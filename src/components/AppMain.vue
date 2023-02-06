<script>

    export default {

        name:'AppMain',
        data() {

            return {
                
            };

        },

};

</script>

<template>

    <div class="main">

        <div class="thumbnail">
            <img src="https://www.dc.com/sites/default/files/dc-hero_20220721_SDCC_62d87621a4d733.05089136_62ded671a6a2c2.47617848.jpg" alt="thumbnail">
        </div>

        <div class="cards">
            <div class="card">
                <img src="https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX" alt="">
                <h3>ciao</h3>
            </div>
        </div>

    </div>
    

</template>

<style lang="scss" scoped>

    .main {
        background-color: black;
        height: 100%;

        .thumbnail {
            color: white;
            width: 100%;
            height: 30%;

            img {
                width: 100%;
                height: 100%;
                object-fit: cover;
            }
        }

        .cards {
            height: 70%;
            width: 70%;
            margin: 0 auto;
            margin-top: 20px;
            display: flex;
            flex-wrap: wrap;

            .card {
                width: calc(100% / 6);
                height: 40%;
                color: white;

                img {
                    height: 100%;
                }
            }
        }
    }

</style>