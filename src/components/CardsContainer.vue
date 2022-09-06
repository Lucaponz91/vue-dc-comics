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
    // console.log(comics);


    export default {
    data() { 
        return{
        comics
        }
    }
}
</script>

<style lang="scss" scoped>
    .card{
        height: 240px;
    }

</style>