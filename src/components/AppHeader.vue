<script>
export default {
    name: "AppHeader"
}
</script>

<template>
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

</template>

<style lang="scss" scoped>
.container {
    margin-top: 20px;
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