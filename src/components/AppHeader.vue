<script>

    export default {

        name:'AppHeader',
        data() {

            return {
                
            };

        },

};

</script>

<template>

    <div class="header">
        <div class="logo">
            <img src="../assets/img/dc-logo.png" alt="DC LOGO">
        </div>
        <div class="link">
            <ul>
                <li>
                    <a href="#">characters</a>
                    <a href="#">comics</a>
                    <a href="#">movies</a>
                    <a href="#">tv</a>
                    <a href="#">games</a>
                    <a href="#">collectibles</a>
                    <a href="#">videos</a>
                    <a href="#">fans</a>
                    <a href="#">news</a>
                    <a href="#">shop</a>
                </li>
            </ul>
        </div>
    </div>

</template>

<style lang="scss" scoped>

    .header {
        width: 70%;
        height: 100px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        margin: 0 auto;

        .logo {
            height: 100%;
            width: 100%;
            display: flex;
            align-items: center;

            img {
                height: 70%;
            }
        }

        ul {
            list-style: none;

            li > a {
                text-decoration: none;
                color: black;
                padding: 30px 10px;
                text-transform: uppercase;
                font-size: 0.8rem;
                font-weight: bold;

                &:hover {
                    color:#0c7cec;
                    border-bottom: 5px solid #0c7cec;
                }
            }
        }
    }

</style>