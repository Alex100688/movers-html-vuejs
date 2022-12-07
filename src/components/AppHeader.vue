<script>
import AppContact from './AppContact.vue';
import AppHero from './AppHero.vue';
export default {
  components: {
    AppContact,
    AppHero,        
  },
  name: "AppHeader",
        
  }
</script>
<template>
  <section class="contact-information">
    <AppContact/>
  </section>
  <section>
    <AppHero/>
  </section>
</template>


<style lang="scss" scoped>
  .contact-information{
    background-color: #6abf17;
    color: #ffff;
    font-size: .875rem;
  }

</style>