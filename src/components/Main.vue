<template>

    <div class="main_container">
        <div>
            <CardsContainer :comics="comics"/>
        </div>

    </div>
</template>


<script>
    import CardsContainer from './CardsContainer.vue'
    import comics from './Comics'
    export default{
    name: "MainContent",
    components: { CardsContainer },
    data () {
        return{
        comics
        }
    },
}
</script>

<style lang="scss" scoped>
    .main_container{
        background-color: black;
        height: 130px;
        color: white;
    }

</style>