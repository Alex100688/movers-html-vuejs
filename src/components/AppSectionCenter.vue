<script>
    export default {
       name:"AppSectionCenter", 
    }
</script>
<template>
    <div class="d-flex flex-column justify-content-center align-items-center">
        <small class="general-small">WE ARE A PROFESSIONAL</small>
        <h2 class="second-title">FULL-SERVICE SOLUTION</h2>
        <div class="row gx-5">
            <div class="col-4">
                <div class="figures-center">
                    <img src="../assets/img/avada-movers-serviceonephoto-final-200x128.jpg" alt="">
                    <h5>Two Man Teams</h5>
                    <p>
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nam neque voluptatem, voluptates quidem perferendis asperiores ipsa libero at ipsam fugiat provident quia similique deserunt eveniet animi suscipit quibusdam aperiam magni!
                    </p>
                    <button type="button" class="general-button">READ MORE</button>
                </div>
            </div>
            <div class="col-4">
                <div class="figures-center">
                    <img src="../assets/img/avada-movers-servicetwophoto-final-200x128.jpg" alt="">
                    <h5>Two Man Teams</h5>
                    <p>
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nam neque voluptatem, voluptates quidem perferendis asperiores ipsa libero at ipsam fugiat provident quia similique deserunt eveniet animi suscipit quibusdam aperiam magni!
                    </p>
                    <button type="button" class="general-button">READ MORE</button>
                </div>
            </div>
            <div class="col-4">
                <div class="figures-center">
                    <img src="../assets/img/avada-movers-servicethreephoto-final-200x128.jpg" alt="">
                    <h5>Two Man Teams</h5>
                    <p>
                        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Nam neque voluptatem, voluptates quidem perferendis asperiores ipsa libero at ipsam fugiat provident quia similique deserunt eveniet animi suscipit quibusdam aperiam magni!
                    </p>
                    <button type="button" class="general-button">READ MORE</button>
            </div>
                </div>
        </div>
    </div>
</template>


<style lang="scss" scoped>
    
    small{
        margin-top: 3.75rem;
        margin-bottom: .625rem;
        font-weight: 900;
    }
    .second-title{
        margin-bottom: 1.25rem;
        color: #6abf17;
        text-align: center;
        font-weight: 900;
    }
    .figures-center{
        border: .9375rem solid #f4f8fb;
        img{
            width: 100%;
            object-fit: cover;
        }
        h5, p{
            text-align: center;
        }
        h5{
            margin-top: 1.5625rem;
            color: #1775bf;
            font-weight: 900;
        }
        p{
            font-size: .875rem;
            padding: 0 1.25rem;
        }
        button{
            margin-bottom: 1.25rem;
            margin-left: 7.5rem;
            width: 6.25rem;
            border-radius: 1.25rem;
        }
    }
</style>