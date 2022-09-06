<template>
  <div class="card_container">
    <div class="card" v-for="(comic, index) in comics" :key="index">
        <a href="#">
            <img :src="comic.thumb" :alt="comic.series">
            <h5>{{ comic.series }}</h5>
        </a>
    </div>
  </div>
</template>

<script>
    import comics from '@/components/Comics'
    console.log(comics);


    export default {
    data() { 
        return{
            comics
        }
    }
}
</script>

<style lang="scss" scoped>
    .card_container{
        // display: flex;
        // flex-wrap: wrap;
        display: grid;
        grid-template-columns: repeat(6, 1fr);
    }
    .card{
        height: 240px;
    }
    img{
        width: 190px;
        aspect-ratio: 1;
        object-fit: cover;
        object-position: top;
    }

</style>