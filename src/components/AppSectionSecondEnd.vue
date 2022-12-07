<script>
    export default {
       name:"AppSectionSecondEnd", 
    }
</script>
<template>
    <div class="d-flex flex-column justify-content-center align-items-center second-end">
        <h2>Testimonials</h2>
        <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Aliquid dolores facilis provident voluptate dignissimos porro dolorum? Voluptatum incidunt magni iusto ipsam error magnam expedita mollitia neque ex natus, iste perspiciatis!.</p>
        <button type="button" class="general-button">CLICK HERE</button>
    </div>
</template>


<style lang="scss" scoped>
    .second-end{
        background-image: url(../assets/img/avada-movers-request-quote-background.jpg);
        margin-top: 3.75rem;
    }
    h2, p{
        text-align: center;
    }
     h2{
        margin-top: 1.875rem;
        font-weight: 900;
        color: #6abf17;
    }
    p{
        font-size: .875rem;
        font-weight: 900;
        color: #7777;
    }
    button{
            margin-top: .625rem;
            margin-bottom: 1.25rem;
            width: 6.25rem;
            border-radius: 1.25rem;
        }
</style>