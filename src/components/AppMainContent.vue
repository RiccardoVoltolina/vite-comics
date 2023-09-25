<script>

import cards from "../card.js"
import productItem from "../components/productItem.vue"

 

export default{

    name: 'AppMainContent',
    components: {
        productItem
    },

    data() {
        return {
            cards
        }
    },
    

}
</script>

<template>

    <productItem :image="card.thumb" :title="card.series" v-for="(card, i) in cards.cards"> </productItem>
<!--     <main class="">
        <section class="bg_image"></section>
        <section class="color_dark">
            <div class="container w-75 g-0 position-relative">
                <h3 class="current_series">CURRENT SERIES</h3>
                <div class="row g-0 pt-5">
                    <div class="col-2 p-3" v-for="(card, i) in cards.cards">
                        <div class="d-flex flex-column">
                            <img :src="card.thumb" alt="">
                            <h5 class="text-white">{{ card.series }}</h5>
                        </div>
                    </div>
                    <div class="pb-3">

                        <h3 class="load_more">LOAD MORE</h3>
                    </div>

                    
                </div>
            </div>
        </section>

    </main>
 --></template>

<style lang="scss" scoped>
    main {
        .bg_image {
            height: 300px;
            background-image: url(../img/jumbotron.jpg);
            background-size: cover;
        }

        .color_dark {
            background-color: #1c1c1c;
        }

        .current_series {
            top: -20px;
            padding: 10px;
            position: absolute;
            color: white;
            background-color: #0282f9;
            width: fit-content;
            font-size: 15px;
        }

        img {
            max-width: 300px;
            aspect-ratio: 1;
        }

        h5 {
            font-size: 13px;
            padding-top: 1rem;
        }

        .load_more {
            background-color: #0282f9;
            width: fit-content;
            font-size: 12px;
            margin: auto;
            color: white;
            padding: 10px 50px;


        }
    }
</style>
