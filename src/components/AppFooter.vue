<script>
import FirstFooter from './FirstFooter.vue';
import FooterInformation from './FooterInformation.vue';
export default {
        components: {
        FirstFooter,
        FooterInformation,
        },
    name: "AppFooter"
        
    }
</script>
<template>
    <div>
        <FirstFooter class="container"/>
    </div>
    <div class="footer-information">
        <FooterInformation class="container"/>
    </div>
</template>


<style lang="scss" scoped>
    .footer-information{
        margin-top: 2.5rem;
        background-color: #6abf17;
        color: #ffff;
    }
</style>