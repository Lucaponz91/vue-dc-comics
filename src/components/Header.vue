<template>
    <div class="header_container">
        <img src="@/assets/dc-logo.png" alt="logo">
        <ul>
            <li><a href="">CHARACTERS</a></li>
            <li><a href="">COMICS</a> </li>
            <li><a href="">MOVIES</a></li>
            <li><a href="">TV</a></li>
            <li><a href="">GAMES</a></li>
            <li><a href="">COLLECTIBLES</a></li>
            <li><a href="">VIDEOS</a></li>
            <li><a href="">FANS</a></li>
            <li><a href="">NEWS</a></li>
            <li><a href="">SHOP</a></li>
            
        </ul>

    </div>
    
</template>

<script>
    export default{
        name: 'MainHeader'
    }
</script>

<style lang="scss" scoped>
    .header_container{
        height: 120px;
        max-width: 1920px;
        display:flex;
        justify-content: space-between;
        align-items: center;
        ul{
            display: flex;
            li{
                padding: 15px;
                font-weight: 800;
                &:hover{
                    border-bottom: 4px solid blue;
                }
            }
        }
    }

</style>