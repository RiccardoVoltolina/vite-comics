<script>
export default {
    name: 'prductItem',
    props: ['image', 'title', 'cardsArray', 'cards', 'card']
}

</script>

<template>
   
    <div class="col-2 p-3">
        <div class="d-flex flex-column">
            <img :src="image" alt="">
            <h5 class="text-white">{{ title }}</h5>
        </div>
    </div>
                  
                    
 

</template>

<style lang="scss" scoped>
      img {
            max-width: 300px;
            aspect-ratio: 1;
        }
        h5 {
            font-size: 13px;
            padding-top: 1rem;
        }
</style>
