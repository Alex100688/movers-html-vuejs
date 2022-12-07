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
            <ul>
                <li>Home</li>
                <li>Rates</li>
                <li>Testimonials</li>
                <li>Blog</li>
                <li>Free Quote</li>
            </ul>
        </div>
        <div class="col-4">
            <h6>RECENT POSTS</h6>
            <ul>
                <li>Heading out to college</li>
                <li>Moving your business</li>
                <li>Outstading quality</li>
                <li>Cost of Moving</li>
                <li>Best Moving Tips</li>
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
    
    p, ul{
        font-size: .875rem;
        color: #7777;
    }
</style>