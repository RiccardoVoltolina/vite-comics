<script>


 

export default{

    name: 'AppHeader',

    data() {
        return {
            navSections: ['CHARACTERS', 'COMICS', 'MOVIES', 'TV', 'GAMES', 'COLLECTIBLES', 'VIDEOS', 'FANS', 'NEWS', 'SHOP' ]
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
                <a v-for="(navSection, i) in navSections" href="">{{ navSection }}</a>
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
