<script>


 

export default{

    name: 'AppHeader',

    data() {
        return {

        }
    },
    

}
</script>

<template>
  <header>
    <div class="container w-75 py-4">
        <div class="row">
            <div class="col-4">
                <img src="../../src/img/dc-logo.png" alt="">
            </div>
            <div class="col-8 d-flex justify-content-between align-items-center">
                <a href="">CHARACTERS</a>
                <a href="">COMICS</a>
                <a href="">MOVIES</a>
                <a href="">TV</a>
                <a href="">GAMES</a>
                <a href="">COLLECTIBLES</a>
                <a href="">VIDEOS</a>
                <a href="">FANS</a>
                <a href="">NEWS</a>
                <a href="">SHOP</a>
            </div>
            
        </div>
        
    </div>
  </header>
</template>

<style lang="scss" scoped>

    img {
        height: 90px;
        width: 90px;
    }

    a {
        text-decoration: none;
        color: black;
    }

</style>
