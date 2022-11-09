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
        <img :src="comic.thumbs" alt="">
        <h4>{{ comic.series }}</h4>
    </div>

</template>

<style lang="scss" scoped>
.card {
    background-color: rgb(31, 29, 29);
    width: calc(100% / 6 - 10px);
    margin: 5px;
}
</style>