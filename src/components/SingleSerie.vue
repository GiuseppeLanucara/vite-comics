<script>
export default {
    name: "SingleSerie",
    props: {
        comic: Object
    }
}
</script>

<template>
    <div class="card">
        <img :src="comic.thumb" alt="">
        <h4>{{ comic.series }}</h4>
    </div>

</template>

<style lang="scss" scoped>
.card {
    background-color: rgb(31, 29, 29);
    width: calc(100% / 6 - 10px);
    margin: 5px;
    margin-top: 3rem;

    h4 {
        color: white;
        margin-top: 1rem;
        margin-bottom: 1rem;
    }

    img {
        height: 200px;
        width: 200px;
    }
}
</style>