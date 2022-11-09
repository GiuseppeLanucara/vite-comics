<script>
export default {
    name: "AppHeader",

    data() {
        return {
            pages: [
                {
                    title: "Characters",
                    href: "/characters",
                    active: false,
                },

                {
                    title: "Comics",
                    href: "/comics",
                    active: true,
                },

                {
                    title: "Movies",
                    href: "/movies",
                    active: false,
                },

                {
                    title: "TV",
                    href: "/tv",
                    active: false,
                },

                {
                    title: "Games",
                    href: "/games",
                    active: false,
                },

                {
                    title: "Collectibles",
                    href: "/collectibles",
                    active: false,
                },

                {
                    title: "Video",
                    href: "/video",
                    active: false,
                },

                {
                    title: "Fans",
                    href: "/fans",
                    active: false,
                },

                {
                    title: "News",
                    href: "/news",
                    active: false,
                },

                {
                    title: "Shop",
                    href: "/shop",
                    active: false,
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
                <li v-for="pages in pages" :key="pages">
                    <a :class="{ 'active': pages.active }" href={{pages.href}}>{{ pages.title }}</a>
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
    line-height: 100%;


    &.active {

        color: rgb(0, 102, 255);
        border-bottom: 2px solid blue;
        line-height: 100%;
    }

    &:hover {
        color: rgb(0, 102, 255);

    }

}
</style>