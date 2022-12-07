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
    <div class="container">
        <div class="background-first">
            <AppSectionStart/>
        </div>
        <div>
            <AppSectionCenter/>
        </div>
        <div class="center-under">
            <AppSectionCenterUnder/>
        </div>
        <div>
            <AppSectionEnd/>
        </div>

    </div>
</template>


<style lang="scss" scoped>
    .background-first{
        background-color: #f4f8fb;
    }
    .center-under{
        margin-top: 3.75rem;
        background-image: url(../assets/img/avada-movers-movewithease-background-new.jpg);
        position: relative;
    }
</style>