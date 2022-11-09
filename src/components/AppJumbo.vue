<script>
export default {
    name: "AppJumbo",
}
</script>


<template>
    <div class="background-container">
        <div class="container">
            <div class="series">
                <h2>CURRENT SERIES</h2>
            </div>
        </div>
    </div>

</template>


<style lang="scss" scoped>
.background-container {
    width: 100%;
    height: 400px;
    background-image: url("../assets/img/jumbotron.jpg");

    .container {
        width: 80%;
        margin: 0 auto;
        position: relative;

        .series {
            background-color: rgb(0, 102, 255);
            position: absolute;
            top: 370px;
            left: 0;

            h2 {
                padding: 1rem;
                color: white;
            }
        }
    }
}
</style>