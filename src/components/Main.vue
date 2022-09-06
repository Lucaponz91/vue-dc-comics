<template>

    <div class="main_container">
        <div>
            <CardsContainer/>
        </div>

    </div>
</template>


<script>
    import CardsContainer from './CardsContainer.vue'
    export default{
    name: "MainContent",
    components: { CardsContainer }
}
</script>

<style lang="scss" scoped>
    .main_container{
        background-color: black;
        height: 130px;
        color: white;
    }

</style>