<script>
export default {
    name: "AppBluebar"
}
</script>

<template>

    <div class="background-container">
        <div class="container">
            <ul>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-comics-digital-comics.png" alt="">
                        <span>DIGITAL COMICS</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-comics-merchandise.png" alt="">
                        <span>DC MERCHANDISE</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-comics-subscriptions.png" alt="">
                        <span>SUBSCRIPTION</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-comics-shop-locator.png" alt="">
                        <span>COMIC SHOP LOCATOR</span>
                    </a>
                </li>
                <li>
                    <a href="">
                        <img src="../assets/img/buy-dc-power-visa.svg" alt="">
                        <span>DC POWER VISA</span>
                    </a>
                </li>
            </ul>
        </div>
    </div>

</template>


<style lang="scss" scoped>
.background-container {
    background-color: rgba(0, 110, 255, 0.89);


    .container {
        color: rgba(0, 110, 255, 0.89);
        ;
        margin: 0 auto;
        width: 80%;
        display: flex;
        justify-content: space-around;


        ul {
            display: flex;
            justify-content: space-between;


        }


        li {
            &:hover {
                transform: scale(1.2);
                transition: 2s;
            }
        }

        a {
            display: flex;
            align-items: center;
            padding: 1rem;
            justify-content: space-between;

            img {

                height: 60px;

            }

            span {
                color: white;
                padding-right: 3rem;
                padding-top: 3rem;
                padding-bottom: 3rem;
                padding-left: 1rem;

            }
        }
    }
}
</style>