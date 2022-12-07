<script>
import FirstFooter from './FirstFooter.vue';
import FooterInformation from './FooterInformation.vue;'
export default {
        components: {
        FirstFooter,
        FooterInformation,
        },
    name: "AppFooter"
        
    }
</script>
<template>
    <div class="container">
        <FirstFooter/>
    </div>
    <div class="container">
        <FooterInformation/>
    </div>
</template>


<style lang="scss" scoped>

</style>