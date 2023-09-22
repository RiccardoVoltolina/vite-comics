<script>


 

export default{

    name: 'AppFooter1',

    data() {
        return {
            
        }
    },
    

}
</script>

<template>
    <section>
        <div class="container w-75 d-flex justify-content-start">
            <div class="d-flex flex-column">
                <h3>DC COMICS</h3>
                <a href="">Characters</a>
                <a href="">Comics</a>
                <a href="">Movies</a>
                <a href="">TV</a>
                <a href="">Games</a>
                <a href="">Videos</a>
                <a href="">News</a>
           
                <h3>SHOP</h3>
                <a href="">Shop DC</a>
                <a href="">Shop DC Collectibles</a>
            </div>
            <div class="d-flex flex-column ps-5">
                <h3 class="">DC</h3>
                <a href="">Terms Of Use</a>
                <a href="">Privacy Policy (New)</a>
                <a href="">Add Choices</a>
                <a href="">Advertising</a>
                <a href="">Jobs</a>
                <a href="">Subscription</a>
                <a href="">Talent Workshops</a>
                <a href="">CPSC Certificates</a>
                <a href="">Ratings</a>
                <a href="">Shop Help</a>
                <a href="">Contact Us</a>
            </div>
            <div class="d-flex flex-column ps-5">
                <h3>SITES</h3>
                <a href="">DC</a>
                <a href="">MAD Magazine</a>
                <a href="">DC Kids</a>
                <a href="">DC Universe</a>
                <a href="">DC Power Visa</a>
            </div>

            

            <img src="../img/dc-logo-bg.png" alt="">
            

            
          
           

        </div>
    </section>

</template>

<style lang="scss" scoped>
    section {
        background-image: url(../img/footer-bg.jpg);
        background-repeat: no-repeat;
        background-size: cover;
        

        h3 {
            color: white;
            padding-top: 5px;
            padding-bottom: 5px;
            padding-top: 35px;
            font-size: 25px;
        }

        a {
            text-decoration: none;
            color: gray;
        }

        img {
            margin-top: -3rem;
            margin-bottom: -3rem;
            margin-left: 10rem;
            height: 600px;
        }
    }
</style>
