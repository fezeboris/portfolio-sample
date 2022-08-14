<template>
    <div>
 <section class="footer p-5 mt-5">
    <div class="container-lg text-center">
      <div class="row">
        <div class="col">
          <a href="https://wa.link/m7hbt2" target="_blank" class="p-2">
            <!-- <box-icon type="logo" name="whatsapp"></box-icon
          > -->
            <i class="bx bxl-whatsapp bx-border-circle bx-sm"></i>
          </a>

          <a
            target="_blank"
            href="https://twitter.com/BTchouanfe?t=GNB9DSwDRdnnf0WVQD1GQw&s=08"
            class="p-2"
          >
            <!-- <box-icon name="twitter" type="logo"></box-icon
          > -->
            <i class="bx bxl-twitter bx-border-circle bx-sm"></i
          ></a>
          <a
            target="_blank"
            href="https://www.youtube.com/channel/UCb7GIDR1w7VgFAKW5t9Owaw"
            class="p-2"
          >
            <!-- <box-icon name="twitter" type="logo"></box-icon
          > -->
            <i class="bx bxl-youtube bx-border-circle bx-sm"></i
          ></a>

          <a target="_blank" href="https://github.com/fezeboris" class="p-2">
            <!-- <box-icon class="box-icon" type="logo" name="facebook"></box-icon> -->
            <i class="bx bxl-github bx-border-circle bx-sm"></i>
          </a>
          <!-- <i class="bx bxl-facebook-square bx-border-circle"></i> -->
        </div>
      </div>
      <div class="container-lg text-center">
        <p>
          <small class="mb-5"
            >Copyright@{{ year }} Tchouanfe. All Rights Reserved</small
          >
        </p>

        <p><small>built by Boris Tchouanfe</small></p>
      </div>
    </div>
  </section>
    </div>
</template>

<script>
    export default {
    data() {
            return {
                year: "",
            }
    },

    mounted() {
         let date = new Date();
    this.year = date.getFullYear();
  
    },
    }
    
</script>

<style lang="scss" scoped>

</style>