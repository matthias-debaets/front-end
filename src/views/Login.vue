<template>
    <section class="section section-shaped section-lg my-0">
        <div class="shape shape-style-1 bg-gradient-default">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <span></span>
        </div>
        <section class="section section-lg pt-lg-0 section-contact-us section-contact-us-padding">
    <div class="container">
      <div class="row justify-content-center mt--300">
        <div class="col-lg-8">
          <card gradient="secondary" shadow body-classes="p-lg-5">
            <h4 class="mb-1">Want to work with us?</h4>
            <p class="mt-0">Our partners are very important to us.</p>
            <base-input class="mt-5"
                        alternative
                        placeholder="Your name"
                        addon-left-icon="ni ni-user-run">
            </base-input>
            <base-input alternative
                        placeholder="Email address"
                        addon-left-icon="ni ni-email-83">
            </base-input>
            <base-input class="mb-4">
                                    <textarea class="form-control form-control-alternative" name="name" rows="4"
                                              cols="80" placeholder="Type a message..."></textarea>
            </base-input>
            <base-button type="default" round block size="lg">
              Send Message
            </base-button>
          </card>
        </div>
      </div>
    </div>
  </section>
    </section>
</template>
<script>
export default {};
</script>
<style>
.section-contact-us-padding{
    margin-top: 35%;
    margin-bottom: 5%
}
</style>
