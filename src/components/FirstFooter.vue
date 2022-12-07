<script>
    export default {
    name:"FirstFooter",
    }
</script>
<template>
    <div class="row gx-5 mt-5">
        <div class="col-4">
            <h6>ABOUT</h6>
                <p>
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat, reiciendis voluptatum nesciunt aliquam ex, eligendi magnam odit quam consequatur dolorem laboriosam numquam. Ad, velit voluptate. Ducimus ex tenetur sapiente cum!
                </p>
                <img src="../assets/img/avada-movers-retinalogo.png" alt="">
        </div>
        <div class="col-4">
            <h6>AVADA MOVERS</h6>
            <ul class="special-footer">
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Home</li>
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Rates</li>
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Testimonials</li>
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Blog</li>
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Free Quote</li>
            </ul>
        </div>
        <div class="col-4">
            <h6>RECENT POSTS</h6>
            <ul>
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Heading out to college</li>
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Moving your business</li>
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Outstading quality</li>
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Cost of Moving</li>
                <li><i class="fa-solid fa-chevron-right mx-3"></i>Best Moving Tips</li>
            </ul>
        </div>
    </div>
</template>


<style lang="scss" scoped>
    img{
        margin-top: .9375rem;
        max-width: 6.25rem;
        max-height: 6.25rem;
    }
    h6, p{
        text-align: center;
    }
    .special-footer > li:first-child{
        color: #6abf17;
    }
    ul{
        list-style: none;
    }
    li {
        margin-bottom: .625rem;
        margin-left: 4.375rem;
       
    }
    p, ul{
        font-size: .8125rem;
    }
</style>