<script>
import AppSectionStar from './AppSectionStar.vue'
export default {
    components: {
        AppSectionStar,
        },
    name:"AppMain"   
    }
</script>
<template>
    <div class="background-first">
        <AppSectionStar class="container "/>
    </div>
</template>


<style lang="scss" scoped>
    .background-first{
        background-color: #f4f8fb;
    }
</style>