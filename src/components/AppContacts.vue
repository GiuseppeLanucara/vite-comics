<script>
export default {
    name: "AppContacts"
}
</script>


<template>
    <div class="background-container">
        <div class="container">
            <div class="login">
                <button><a href="">SIGN-UP NOW!</a></button>
            </div>
            <div class="socials">
                <a href="">
                    <h2>FOLLOW US</h2>
                </a>
                <a href=""> <img src="../assets/img/footer-facebook.png" alt=""></a>
                <a href=""><img src="../assets/img/footer-twitter.png" alt=""></a>
                <a href=""><img src="../assets/img/footer-youtube.png" alt=""></a>
                <a href=""><img src="../assets/img/footer-pinterest.png" alt=""></a>
                <a href=""><img src="../assets/img/footer-periscope.png" alt=""></a>
            </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
.background-container {
    width: 100%;
    background-color: rgb(27, 27, 27);

    .container {
        width: 80%;
        margin: 0 auto;
        display: flex;
        justify-content: space-between;
        align-items: center;

        .login {
            display: flex;
            align-items: center;
            padding-top: 2rem;
            padding-bottom: 2rem;

            button {
                background-color: rgb(27, 27, 27);
                border: 2px solid rgb(0, 81, 255);
                padding: 1rem;

                a {
                    color: white;
                    padding: 1rem;

                    &:hover {

                        button {
                            border-color: rgb(0, 132, 255);
                        }

                        color: rgba(255, 255, 255, 0.795);
                    }
                }
            }
        }

        .socials {
            display: flex;
            align-items: center;



            h2 {
                color: rgb(0, 102, 255);
            }

            img {
                padding-right: 1rem;
                padding-left: 1rem;

                &:hover {
                    transform: scale(1.5);
                    transition: 1s;
                }
            }
        }
    }
}
</style>