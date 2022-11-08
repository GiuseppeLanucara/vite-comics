<script>
export default {
    name: "Main"
}
</script>

<template>
    <div class="background-container">
        <div class="container">
            <h2> --Content Goes Here-- </h2>
        </div>
    </div>

</template>


<style lang="scss" scoped>
.background-container {
    background-color: rgb(31, 29, 29);

    .container {
        width: 80%;
        margin: auto;
        background-color: rgb(31, 29, 29);
        display: flex;
        align-items: center;
        justify-content: flex-start;

        h2 {
            color: white;
            padding-top: 3rem;
            padding-bottom: 3rem;
        }
    }
}
</style>