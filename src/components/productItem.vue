<script>
export default {
    name: 'prductItem',
    props: ['image', 'title', 'cardsArray']
}

</script>

<template>
    <main class="">
        <section class="bg_image"></section>
        <section class="color_dark">
            <div class="container w-75 g-0 position-relative">
                <h3 class="current_series">CURRENT SERIES</h3>
                <div class="row g-0 pt-5">
                    <div class="col-2 p-3" v-for="(card, i) in cards.cardsArray">
                        <div class="d-flex flex-column">
                            <img :src="image" alt="">
                            <h5 class="text-white">{{ title }}</h5>
                        </div>
                    </div>
                    <div>

                        <h3 class="load_more">LOAD MORE</h3>
                    </div>

                    
                </div>
            </div>
        </section>

    </main>

 

</template>

<style>
</style>
