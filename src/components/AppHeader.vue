<script>


 

export default{

    name: 'AppHeader',

    data() {
        return {
            navSections: ['CHARACTERS', 'COMICS', 'MOVIES', 'TV', 'GAMES', 'COLLECTIBLES', 'VIDEOS', 'FANS', 'NEWS', 'SHOP' ],
            isHovered:false,
            barraColore:'',
        }
    },
    methods: {
        setHover(valore) {
            this.isHovered = valore;
            console.log(this.isHovered);
        },

        styleCss(stileBarra){
            if (stileBarra == true) {
                return {
                    'border-bottom': '2px solid #0282f9',
                    'color': '#0282f9',
                }
                return '';
            }
        }
    }

}
</script>

<template>
  <header>
    <div class="container w-75 pt-4">
        <div class="row">
            <div class="col-4 pb-4">
                <img src="../../src/img/dc-logo.png" alt="">
            </div>
            <div class="col-8 d-flex justify-content-between align-items-center">
                <div v-for="(navSection, i) in navSections" class="d-flex align-items-center h-100" :class="{'hover_blue' : navSection.isHovered}">
                    {{ barraColore }}

                    <a @mouseover="setHover(true)" @mouseout="setHover(false)" href="">{{ navSection }}</a>
                </div> 

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
        align-items: center;
        display: flex;
        height: 100%;
    }

    a:hover {
        color: #0282f9;
        border-bottom: 2px solid #0282f9;
        color: #0282f9;

    }

  

</style>
