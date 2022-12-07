<script>
import AppHeader from './components/AppHeader.vue';
import AppMain from './components/AppMain.vue';
import AppFooter from './components/AppFooter.vue';
export default {
  components:
  { AppHeader,
    AppMain,
    AppFooter     
  },
}
</script>
<template>
  <div>
    <AppHeader/>
    <AppMain/>
    <AppFooter/>
  </div>
</template>


<style lang="scss">
@import "./style/global.scss";
@import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700;900&display=swap');
.general-button{
  background-color: #1775bf;
  color: #ffff;
  font-size: .875rem;
  font-weight: 900;
}
.general-small{
  color: #777777;
  font-size: .75rem;
}
</style>
