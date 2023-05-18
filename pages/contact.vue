<template>
  <main>
    <section class="page_breadcrumbs ls background_cover section_padding_50">
      <div class="container">
        <div class="row">
          <div class="col-xs-12 text-center">
            <h1 class="sr-only">Contact 2</h1>
            <ol class="breadcrumb darklinks">
              <li><a href="./"> Home </a></li>
              <li><a href="/">Pages</a></li>
              <li class="active"><span>Contact 2</span></li>
            </ol>
          </div>
        </div>
      </div>
    </section>
    <section class="ls section_padding_top_150 section_padding_bottom_150">
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <section
              id="map"
              class="ls ms"
              data-address="522 Chapel St, South Yarra VIC 3141, Australia"
            >
              <!-- marker description and marker icon goes here -->
              <div class="map_marker_description">
                <h3>Map Title</h3>
                <p>Map description text</p>
                <img
                  class="map_marker_icon"
                  src="~/assets/images/map_marker_icon.png"
                  alt=""
                />
              </div>
            </section>
          </div>
        </div>
        <div class="row topmargin_40">
          <div class="col-sm-4 to_animate" data-animation="pullDown">
            <div class="teaser text-center">
              <div class="teaser_icon highlight size_normal">
                <i class="rt-icon2-phone5"></i>
              </div>
              <p>
                <span class="grey">Phone:</span> +12 345 678 9123<br />
                <span class="grey">Fax:</span> +12 345 678 9123
              </p>
            </div>
          </div>
          <div class="col-sm-4 to_animate" data-animation="pullDown">
            <div class="teaser text-center">
              <div class="teaser_icon highlight size_normal">
                <i class="rt-icon2-location2"></i>
              </div>
              <p>
                PO Box 54378<br />
                4321 Your Address,<br />
                Your City, Your Country
              </p>
            </div>
          </div>
          <div class="col-sm-4 to_animate" data-animation="pullDown">
            <div class="teaser text-center">
              <div class="teaser_icon highlight size_normal">
                <i class="rt-icon2-mail"></i>
              </div>
              <p>support@yourname.com</p>
            </div>
          </div>
        </div>
        <div class="row topmargin_40">
          <div class="col-sm-12 to_animate">
            <form class="contact-form" method="post" action="./">
              <div class="row">
                <div class="col-sm-6">
                  <p class="form-group">
                    <label for="name"
                      >Full Name <span class="required">*</span></label
                    >
                    <i class="fa fa-user highlight" aria-hidden="true"></i>
                    <input
                      id="name"
                      type="text"
                      aria-required="true"
                      size="30"
                      value=""
                      name="name"
                      class="form-control"
                      placeholder="Full Name"
                    />
                  </p>
                  <p class="form-group">
                    <label for="email"
                      >Email address<span class="required">*</span></label
                    >
                    <i class="fa fa-envelope highlight" aria-hidden="true"></i>
                    <input
                      id="email"
                      type="email"
                      aria-required="true"
                      size="30"
                      value=""
                      name="email"
                      class="form-control"
                      placeholder="Email Address"
                    />
                  </p>
                  <p class="form-group">
                    <label for="subject"
                      >Subject<span class="required">*</span></label
                    >
                    <i class="fa fa-flag highlight" aria-hidden="true"></i>
                    <input
                      id="subject"
                      type="text"
                      aria-required="true"
                      size="30"
                      value=""
                      name="subject"
                      class="form-control"
                      placeholder="Subject"
                    />
                  </p>
                </div>
                <div class="col-sm-6">
                  <p class="contact-form-message form-group">
                    <label for="message">Message</label>
                    <i class="fa fa-comment highlight" aria-hidden="true"></i>
                    <textarea
                      id="message"
                      aria-required="true"
                      rows="6"
                      cols="45"
                      name="message"
                      class="form-control"
                      placeholder="Message"
                    ></textarea>
                  </p>
                </div>
              </div>
              <div class="row">
                <div class="col-sm-12">
                  <p class="contact-form-submit text-center topmargin_10">
                    <button
                      id="contact_form_submit"
                      type="submit"
                      name="contact_submit"
                      class="theme_button color1 margin_0"
                    >
                      Send Message
                    </button>
                  </p>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
    <section class="ls section_padding_top_150 section_padding_bottom_150">
      <div class="container">
        <div class="row">
          <div
            class="col-xs-12 col-sm-8 col-md-6 col-sm-offset-2 col-md-offset-3 text-center"
          >
            <h2 class="section_header small">Our Newsletter</h2>
            <p class="small-text grey">subscribe</p>
            <div class="widget widget_mailchimp">
              <form class="signup" action="./" method="get">
                <div class="form-group">
                  <input
                    class="mailchimp_email form-control"
                    name="email"
                    type="email"
                    placeholder="Email Address"
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
    <gallery-scroll />
  </main>
</template>
<script>
import GalleryScroll from '@/components/galleryScroll.vue'
export default {
  components: {
    GalleryScroll,
  },
}
</script>
