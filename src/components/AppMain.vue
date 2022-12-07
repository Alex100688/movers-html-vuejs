<script>
import AppSectionStart from './AppSectionStart.vue'
export default {
    components: {
        AppSectionStart,
        },
    name:"AppMain"   
    }
</script>
<template>
    <div class="background-first">
        <AppSectionStart class="container "/>
    </div>
</template>


<style lang="scss" scoped>
    .background-first{
        background-color: #f4f8fb;
    }
</style>