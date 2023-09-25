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

    </main>
</template>

<style lang="scss" scoped>
    main {
        .bg_image {
            height: 300px;
            background-image: url(../img/jumbotron.jpg);
            background-size: cover;
        }
    }
</style>
