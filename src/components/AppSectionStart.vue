<script>
    export default {
        name:"AppSectionStart",
    }
</script>
<template>
    <div class="d-flex flex-column justify-content-center align-items-center margin-section">
        <small class="general-small">HEADACHE FREE</small>
        <div class="second-title">
            <h2>Award Winning</h2>
            <h2>Moving Company</h2>
        </div>
        <p>
            Lorem ipsum dolor sit amet, consecteur adiphising elit. Nullam ac ague. Orci varius natoque penatibus et
            magnis dis parturient montes, ridilus mus. Alquam enim leo, condimentum facilisis nulla sed, cursurs
            arcu. <br> Aliquam enim leo.
        </p>
        <button type="button" class="general-button">READ OUR TESTIMONIALS</button>
    </div>
</template>


<style lang="scss" scoped>
    .margin-section{
        margin-top: 3.75rem;
    }
    small{
        margin-top: 1.25rem;
        margin-bottom: .625rem;
        font-weight: 900;
        
    }
    .second-title{
        margin-bottom: 1.25rem;
        color: #6abf17;
        h2{
            text-align: center;
            font-weight: 900;
        }
    }
    p{
        text-align: center;
        color:#777777;
    }
    button{
        margin-top: 1.25rem;
        width: 15.625rem;
        height: 1.875rem;
        border-radius: 1.875rem;
    }
</style>