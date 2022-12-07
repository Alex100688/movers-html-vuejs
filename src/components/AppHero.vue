    <script>
        export default {
           name: "AppHero",
        }
    </script>
<template>
    <div class="container hero">
        <div class="row">
            <div class="col-12 d-flex justify-content-between align-items-center">
                <div class="my-2 mx-2">
                   <img src="../assets/img/avada-movers-logo.png" alt="">
                </div>
                <div class="d-flex my-3 ">
                    <ul class="d-flex general-typography">
                        <li class="px-4 special">Home</li>
                        <li class="px-4">Rates</li>
                        <li class="px-4">Testimonials</li>
                        <li class="px-4">FAQ</li>
                        <li class="px-4">Blog</li>
                        <li class="px-4">Contact</li>
                    </ul>
                    <button type="button" class="general-button">FREE QUOTE</button>
                </div>
            </div>
        </div>
        <div class="d-flex flex-column justify-content-center align-items-center hero-title">
            <small class="my-1 general-small">MOVING WITHOUT THE HASSLE</small>
            <h1>WE MAKE IT SIMPLE</h1>
            <small class="my-1 general-small">PROFESSIONAL SERVICE WITH QUALITY AND CUSTOMER SATISFACTION</small>
        </div>
    </div>
    <div class="final-link">
        <i class="fa-solid fa-location-arrow"></i><small class="mx-2">GET A FREE QUOTE ONLINE NOW!</small>
    </div>
   
</template>


<style lang="scss" scoped>
    .hero{
        background-image: url(../assets/img/avada-movers-homeherobackground-final.jpg)
    }
    img{
        max-width: 6.25rem;
        max-height: 6.25rem;
    }
    .general-typography{
        font-size: .875rem;
        font-weight: 900;
    }
    ul{
        list-style: none;
        .special{
            color: #6abf17;
        }
    }
    
    button{
        width: 8.125rem;
        height: 1.75rem;
        border-radius: 20%;
        border: none;
        text-align: center;
        line-height: 1.875rem;
    }
    .hero-title{
        margin-top: 4.0625rem;
        h1{
            font-size: 3.125rem;
        }
        h1, small{
            font-weight: 900;
        }
    }
    .final-link{
        margin: 6.25rem;
        background-color: #1775bf;
        color: #ffff;
        height:3.75rem ;
        text-align: center;
        line-height: 3.75rem;
        small{
            font-size: .75rem;
        }
    }
</style>