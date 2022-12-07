<script>
    export default {
       name:"AppSectionEnd", 
    }
</script>
<template>
   <div class="d-flex flex-column justify-content-center align-items-center section-end">
        <small class="general-small mt-5">HAPPY CUSTOMERS</small>
        <h2>Testimonials</h2>
        <div class="row  mt-5">
            <div class="col-4">
                <div class="circle-figures">
                    <img src="../assets/img/avada-movers-johndoe-final-200x200.jpg" alt="">
                    <h5>John Doe</h5>
                        <p>
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nam neque voluptatem, voluptates quidem perferendis asperiores ipsa libero at ipsam fugiat provident.
                        </p>
                </div>    
            </div>   
            <div class="col-4">
                <div class="circle-figures">
                    <img src="../assets/img/avada-movers-janedoe-final-200x200.jpg" alt="">
                    <h5>Jane Doe</h5>
                        <p>
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nam neque voluptatem, voluptates quidem perferendis asperiores ipsa libero at ipsam fugiat provident.
                        </p>
                </div>   
            </div>  
            <div class="col-4">
                <div class="circle-figures">
                    <img src="../assets/img/avada-movers-johnsmith-final-200x200.jpg" alt="">
                    <h5>John Doe</h5>
                        <p>
                            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nam neque voluptatem, voluptates quidem perferendis asperiores ipsa libero at ipsam fugiat provident.
                        </p>
                </div>       
            </div>  
        </div> 
        <button type="button" class="general-button">READ MORE TESTIMONIALS</button>    
    </div>
</template>


<style lang="scss" scoped>
    .section-end{
        background-image: url(../assets/img/avada-movers-testimonial-background.jpg);
        margin-top: 3.75rem;
    }
    h2{
        font-weight: 900;
        color: #6abf17;
    }
    .circle-figures{
        width: 9.375rem;
        margin: 0 6.25rem;
        img{
            width: 100%;
            border-radius: 50%;
            object-fit: cover;
        }
        h5, p{
            text-align: center;
            margin-top: .625rem;
        }
        h5{
            font-weight: 900;
            color:#1775bf;
        }
        p{
            font-size: .875rem;
            font-weight: 900;
            font-style: italic;
            width: 11.25rem;
            color: #7777;
        }
    }
    button{
        margin-top: 2.5rem;
        margin-bottom: 1.5625rem;
        width: 15.625rem;
        border-radius: 1.25rem;
    }
</style>