<script>


 

export default{

    name: 'AppJumbotron',

    data() {
        return {
            
        }
    },
    

}
</script>

<template>
    <section class="py-5">
        <div class="container w-75 d-flex align-items-center justify-content-between">
            <div class="d-flex align-items-center">
                <img src="../img/buy-comics-digital-comics.png" alt="">
                <div class="ps-3">DIGITAL COMICS</div>
            </div>
            <div class="d-flex align-items-center">
                <img src="../img/buy-comics-merchandise.png" alt="">
                <div class="ps-3">DC MERCHANDISE</div>
            </div>
            <div class="d-flex align-items-center">
                <img src="../img/buy-comics-subscriptions.png" alt="">
                <div class="ps-3">SUBSCRIPTION</div>
            </div>
            <div class="d-flex align-items-center">
                <img src="../img/buy-comics-shop-locator.png" alt="">
                <div class="ps-3">COMIC SHOP LOCATOR</div>


            </div>
            <div class="d-flex align-items-center">
                <img src="../img/buy-dc-power-visa.svg" alt="">
                <div class="ps-3">DC POWER VISA</div>
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
