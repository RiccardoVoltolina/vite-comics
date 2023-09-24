<script>


 

export default{

    name: 'AppFooter1',

    data() {
        return {
            dcComicsLinks: ['Characters','Comics', 'Movies','TV','Games', 'Videos', 'News'],
            shopLinks: ['Shop DC', 'Shop DC Collectibles'],
            dcLinks: ['Terms Of Use', 'Privacy Policy (New)', 'Add Choices', 'Advertising', 'Jobs', 'Subscription', 'Talent Workshops', 'CPSC Certificates', 'Ratings', 'Shop Help', 'Contact Us'],
            sitesLinks: ['DC', 'MAD Magazine', 'DC Kids', 'DC Universe', 'DC Power Visa']
            
        }
    },
    

}
</script>

<template>
    <section>
        <div class="container w-75 d-flex justify-content-start">
            <div class="col-5 d-flex">
                
                <div class="d-flex flex-column p_40px">
                    <h3>DC COMICS</h3>
                    <a v-for="(dcComicsLink, i) in dcComicsLinks" href="">{{ dcComicsLink }}</a>
                   
               
                    <h3>SHOP</h3>
                    <a v-for="(shopLink, i) in shopLinks" href="">{{ shopLink }}</a>
                </div>
                <div class="d-flex flex-column ps-5 pb-5">
                    <h3 class="">DC</h3>
                    <a v-for="(dcLink, i) in dcLinks" href="">{{ dcLink }}</a>
            
                </div>
                <div class="d-flex flex-column ps-5">
                    <h3>SITES</h3>
                    <a v-for="(sitesLink, i) in sitesLinks" href="">{{ sitesLink }}</a>
                </div>

            </div>    
            <div class="col-7 immagine_background">
            </div>
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
            font-size: 20px;
        }

        a {
            text-decoration: none;
            color: gray;
            font-size: 10px;            
        }

        .p_40px {
            padding-bottom: 40px;
        }

        .immagine_background {
            margin-top: -70px;
            margin-left: 130px;
            width: 100%;
            background-image: url(../img/dc-logo-bg.png);
            background-repeat: no-repeat;
        }


    }
</style>
