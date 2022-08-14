<template>
    <div>
          <section>
    <div class="container-lg">
      <form action="https://formspree.io/f/xpzbyqqd" method="POST">
        <p class="fs-2 text-center fw-bold about pt-4" id="contact">
          CONTACT ME
        </p>
        <div class="row">
          <div class="col-12 col-md-6 col-lg-6 my-2">
            <input
              type="text"
              required
              class="form-control"
              placeholder="Your Name"
              name="Name"
              v-model="name"
              aria-label="Your name"
            />
            <input
              type="text"
              required
              class="form-control my-2"
              placeholder="Subject"
              aria-label="Subject"
              v-model="subject"
              name="Subject"
            />
            <div class="form-floating mt-2">
              <textarea
                class="form-control"
                placeholder="Leave a comment here"
                id="floatingTextarea2"
                style="height: 100px"
                name="Message"
                v-model="message"
              ></textarea>
              <label for="floatingTextarea2">Message</label>
            </div>
          </div>
          <div class="col-12 col-md-6 col-lg-6 my-2">
            <input
              type="email "
              v-model="email"
              required
              class="form-control"
              placeholder="Your Email"
              aria-label="Your Email"
              name="Email"
            />
          </div>
        </div>
        <div class="container text-center mt-4">
          <button class="btn btn-outline-primary btn" type="submit">
            Send Message
          </button>
        </div>
      </form>
    </div>
    <div class="container-lg text-center mt-5">
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
      
    </div>
  </section>
    </div>
</template>

<script>
    export default {
    data() {
            return {
                
            }
    },

    methods: {
         onsubmit() {
      (this.name = ""),
        (this.email = ""),
        (this.message = ""),
        (this.subject = "");
    },
        
    },
    }
</script>

<style scoped>
.bx-border-circle{
    color: black !important;
}

</style>