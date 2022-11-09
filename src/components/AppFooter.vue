<script>
export default {
    name: "AppFooter"
}
</script>

<template>

    <div class="background-container">
        <div class="container">

            <div class="list">
                <ul>
                    <h2>DC COMICS</h2>
                    <li>
                        <a href="">Characters</a>
                    </li>
                    <li>
                        <a href="">Comics</a>
                    </li>
                    <li>
                        <a href="">Movies</a>
                    </li>
                    <li>
                        <a href="">TV</a>
                    </li>
                    <li>
                        <a href="">Games</a>
                    </li>
                    <li>
                        <a href="">Video</a>
                    </li>
                    <li>
                        <a href="">News</a>
                    </li>

                    <h2>SHOP</h2>
                    <li>
                        <a href="">Shop DC</a>
                    </li>
                    <li>
                        <a href="">Shop DC Collectibles</a>
                    </li>
                </ul>
                <ul>
                    <h2>DC</h2>
                    <li>
                        <a href="">Terms of use</a>
                    </li>
                    <li>
                        <a href="">Privacy Policy(New)</a>
                    </li>
                    <li>
                        <a href="">Ad Choices</a>
                    </li>
                    <li>
                        <a href="">Advertising</a>
                    </li>
                    <li>
                        <a href="">Jobs</a>
                    </li>
                    <li>
                        <a href="">Subscriptions</a>
                    </li>
                    <li>
                        <a href="">Talent Workshop</a>
                    </li>
                    <li>
                        <a href="">CPSC Certificates</a>
                    </li>
                    <li>
                        <a href="">Ratings</a>
                    </li>
                    <li>
                        <a href="">Shop Help</a>
                    </li>
                    <li>
                        <a href="">Contact Us</a>
                    </li>
                </ul>

                <ul>
                    <h2>SITES</h2>
                    <li>
                        <a href="">DC</a>
                    </li>
                    <li>
                        <a href="">MAD Magazines</a>
                    </li>
                    <li>
                        <a href="">DC Kids</a>
                    </li>
                    <li>
                        <a href="">DC Universe</a>
                    </li>
                    <li>
                        <a href="">DC Power Visa</a>
                    </li>
                </ul>
            </div>

            <img id="bglogo" src="../assets/img/dc-logo-bg.png" alt="">

        </div>
    </div>

</template>

<style lang="scss" scoped>
.background-container {
    width: 100%;
    background-image: url("../assets/img/footer-bg.jpg");
    background-size: cover;

    .container {
        width: 80%;
        height: 450px;
        overflow: hidden;
        margin: auto;
        display: flex;
        justify-content: space-between;

        .list {
            display: flex;

            ul {
                color: white;
                padding-bottom: 3.5rem;
                margin-right: 3rem;


                li {
                    padding-top: .5rem;


                }

                h2 {
                    padding-top: 2rem;
                    margin-bottom: .5rem;
                }

                a {
                    color: rgba(255, 255, 255, 0.5);
                    padding-top: .5rem;
                    font-weight: lighter;

                    &:hover {
                        color: antiquewhite;
                    }
                }
            }
        }


    }

    #bglogo {
        display: flex;
        height: 600px;
        margin-top: -100px;

    }
}
</style>