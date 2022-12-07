<script>
import AppSectionStart from './AppSectionStart.vue';
import AppSectionCenter from './AppSectionCenter.vue';
import AppSectionCenterUnder from './AppSectionCenterUnder.vue';
import AppSectionEnd from './AppSectionEnd.vue'
export default {
    components: {
        AppSectionStart,
        AppSectionCenter,
        AppSectionCenterUnder,
        AppSectionEnd,
        },
    name:"AppMain"   
    }
</script>
<template>
    <div class="background-first">
        <AppSectionStart class="container"/>
    </div>
    <div>
        <AppSectionCenter class="container"/>
    </div>
    <div>
        <AppSectionCenterUnder class="container"/>
    </div>
    <div>
        <AppSectionEnd class="container"/>
    </div>

</template>


<style lang="scss" scoped>
    .background-first{
        background-color: #f4f8fb;
    }

</style>