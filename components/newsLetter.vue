<template>
  <section class="ls">
    <div class="container py-24">
      <div class="row">
        <div
          class="col-xs-12 col-sm-8 col-md-6 col-sm-offset-2 col-md-offset-3 text-center"
        >
          <h2 class="section_header small">O nosso boletim informativo</h2>
          <p class="small-text grey">Inscreva-se</p>
          <div class="widget widget_mailchimp">
            <form class="signup" action="./" method="get">
              <div class="form-group">
                <input
                  class="mailchimp_email form-control"
                  name="email"
                  type="email"
                  placeholder="Email"
                />
                <button type="submit" class="theme_button">Sign Up!</button>
              </div>
              <div class="response"></div>
            </form>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: 'BreadcrumbItem',
  props: {
    title: {
      type: String,
      default: 'Home',
    },
    uri: {
      type: String,
      default: '',
    },
  },
}
</script>
