<script>
    export default {
      name:"AppHeader"  
    }
</script>
<template>
  <header>
  <section class="contact-information">
    <div class="container">
        <div class="row ">
          <div class="col-12 d-flex justify-content-between align-items-center my-2 ">
            <div class="ms-4">
              <i class="fa-solid fa-phone-flip"></i>
              <small class="ms-2">Call use for a Free Quote: 1.800.555.6789</small>
            </div>
            <div class="me-4">
              <i class="fa-brands fa-facebook-f px-2"></i>
              <i class="fa-brands fa-twitter px-2"></i>
              <i class="fa-brands fa-instagram px-2"></i>
              <i class="fa-brands fa-youtube px-2"></i>
            </div>
          </div>
        </div>
    </div> 
  </section>
  </header>
</template>


<style lang="scss" scoped>
  .contact-information{
    background-color: #6abf17;
    color: #ffff;
    font-size: .875rem;
  }

</style>