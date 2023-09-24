<script>


 

export default{

    name: 'AppFooter2',

    data() {
        return {
            
        }
    },
    

}
</script>

<template>
    <footer>
        <div class="container w-75">
            <div class="row">
                <div class="col-12 d-flex align-items-center justify-content-between h_150_px">
                    <div class="bottone"><button>SIGN-UP-NOW</button></div>
                    <div class="d-flex align-items-center">
                        <h3>FOLLOW US</h3>
                        <img src="../img/footer-facebook.png" alt="">
                        <img src="../img/footer-twitter.png" alt="">
                        <img src="../img/footer-youtube.png" alt="">
                        <img src="../img/footer-pinterest.png" alt="">
                        <img src="../img/footer-periscope.png" alt="">

                    </div>


                </div>
                
            </div>
        </div>
    </footer>
</template>

<style lang="scss" scoped>
    footer {
        background-color: #303030;
        height: 150px; 

        .h_150_px {

            height: 150px;
            
                    .bottone {
            
            
                        button {
                            background-color: transparent;
                            color: white;
                            border: 2px solid #0282f9;
                            padding: 10px;
                        }
                    }

                    h3 {
                        color: #0282f9;
                    }

                    img {
                        padding-left: 1rem;
                    }
        }
    }

</style>
