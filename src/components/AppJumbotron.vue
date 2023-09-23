<script>
export default{

    name: 'AppJumbotron',

    data() {
        return {
            mainUtilities: [{
                img:"src/img/buy-comics-digital-comics.png",
                utilitiesInfo:'DIGITAL COMICS',
            },
            {
                img:"src/img/buy-comics-merchandise.png",
                utilitiesInfo:'DC MERCHANDISE',
            },
            {
                img:"src/img/buy-comics-subscriptions.png",
                utilitiesInfo: 'SUBSCRIPTION',
            },
            {
                img:"src/img/buy-comics-shop-locator.png",
                utilitiesInfo:'COMIC SHOP LOCATOR',
            },
            {
                img:"src/img/buy-dc-power-visa.svg",
                utilitiesInfo:'DC POWER VISA',
            },
        ]
            
        }
    },

}
</script>

<template>
    <section class="py-5">
        <div class="container w-75 d-flex align-items-center justify-content-between">
            <div v-for="main in mainUtilities" class="d-flex align-items-center">
                <img :src="main.img" alt="">
                <a class="ps-3">{{ main.utilitiesInfo }}</a>
            </div>
            
        </div>
    </section>
</template>

<style lang="scss" scoped>
    img {
        width: 50px;
    }
    section {
        font-size: 10px;
        color: white;
        background-color: #0282f9;
    }
</style>
