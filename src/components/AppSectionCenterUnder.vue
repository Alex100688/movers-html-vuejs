<script>
    export default {
        name:"AppSectionCenterUnder",
    }
</script>
<template>
    <div class="center-under">
       <div class="under">
            <h6 class="mt-5">WE ROMOVE THE HEADACHE FROM MOVING</h6>
            <h2>Move With Ease</h2>
            <hr class="mt-5">
            <p>
                With our super simple service we can take you from getting a quote,
                right throught to begin in your new home with all of your belogings,
                securely pached and safety delivered, even in the rooms of your choice.
            </p>
            <button type="button" class="general-button">GET A FREE QUOTE NOW</button>    
       </div>
    </div>  
</template>


<style lang="scss" scoped>
    .center-under{
        margin-top: 3.75rem;
        background-image: url(../assets/img/avada-movers-movewithease-background-new.jpg);
    }
    .under{
        margin-top: 3.75rem;
        margin-left: 30rem;
        border: 20px solid #5aa511;
        background-color: #6abf17;
        width: 31.25rem;
        
        h6, h2, hr, p, button{
            text-align: center;
            color: #ffff;
            
        }
        h6, h2{
            font-weight: 900;
        }
        p{
            font-size: .8125rem;
            padding: 1.875rem;
        }
        button{
            margin-bottom: 1.875rem;
            margin-left: 8.4375rem;
            width: 12.5rem;
            border-radius: 1.25rem;
        }
    }
</style>