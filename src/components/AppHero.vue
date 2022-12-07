    <script>
        export default {
           name: "AppHero",
        }
    </script>
<template>
    <div class="container">
        <div class="row">
            <div class="col-12 d-flex justify-content-between align-items-center">
                <div class="my-2 mx-2">
                    <img src="../assets/avada-movers-logo.png" alt="">
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
            <small class="my-1">MOVING WITHOUT THE HASSLE</small>
            <h1>WE MAKE IT SIMPLE</h1>
            <small class="my-1">PROFESSIONAL SERVICE WITH QUALITY AND CUSTOMER SATISFACTION</small>
        </div>
    </div>
</template>


<style lang="scss" scoped>
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
        small{
            color: #777777;
            font-size: .75rem;
        }
        h1{
            font-size: 3.125rem;
        }
        h1, small{
            font-weight: 900;
        }
    }
</style>