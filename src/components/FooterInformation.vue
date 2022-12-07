<script>
    export default {
    name:"FooterInformation", 
    }
</script>
<template>
    <div class="d-flex justify-content-center align-items-center ">
        <i class="fa-regular fa-copyright mt-5"></i><small class="mt-5">Copyright 2012-2020 | Avada Theme by ThemeFusion  | All Rights Reserved | Powered by WordPress</small>
    </div>
    <div class="d-flex justify-content-center align-items-center last-social-information ">
        <i class="fa-brands fa-facebook-f px-2"></i>
        <i class="fa-brands fa-twitter px-2"></i>
        <i class="fa-brands fa-instagram px-2"></i>
        <i class="fa-brands fa-youtube px-2"></i>
    </div>
</template>


<style lang="scss" scoped>
    small{
        margin-left: .625rem;
    }
    .last-social-information{
        margin-top: 1.5625rem;
        .fa-brands{
            margin-bottom: 1.875rem;
        }
    
    }
</style>