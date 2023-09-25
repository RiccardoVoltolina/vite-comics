<script>

import cards from "../card.js"

 

export default{

    name: 'AppMainContent',

    data() {
        return {
            cards
        }
    },
    

}
</script>

<template>
    <main class="">
        <section class="bg_image"></section>
        <section class="bg-black">
            <div class="container w-75 g-0">
                <div class="row g-0">
                    <div class="col-2 p-3" v-for="(card, i) in cards.cards">
                        <div class="d-flex flex-column">
                            <img :src="card.thumb" alt="">
                            <h5 class="text-white">{{ card.series }}</h5>
                        </div>
                    </div>
                    
                </div>
            </div>
        </section>

    </main>
</template>

<style lang="scss" scoped>
    main {
        .bg_image {
            height: 300px;
            background-image: url(../img/jumbotron.jpg);
            background-size: cover;
        }

        img {
            max-width: 300px;
            aspect-ratio: 1;
        }

        h5 {
            font-size: 13px;
            padding-top: 1rem;
        }
    }
</style>
