<script>
export default {
    name: "AppHeader",

    data() {
        return {
            pages: [
                {
                    title: "Home",
                    href: "/home",
                    active: false
                }
            ]
        }
    }
}
</script>

<template>
    <div class="background-container">
        <div class="container">
            <img src="../assets/img/dc-logo.png" alt="">

            <ul>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
                <li>
                    <a href="">COMICS</a>
                </li>
            </ul>
        </div>
    </div>


</template>

<style lang="scss" scoped>
.container {
    width: 80%;
    margin: 20px auto;
    margin-bottom: 20px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

ul {
    display: flex;
}

li {
    margin: 0 1rem;
    font-weight: bolder;
}

a {
    &:hover {
        color: rgb(0, 102, 255);
    }
}
</style>