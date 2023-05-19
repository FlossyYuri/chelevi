<template>
  <main>
    <breadcrumb-item title="Home" uri="Contacto" />
    <section class="ls pt-32">
      <div class="container">
        <div class="row">
          <div class="col-sm-12">
            <section class="ls ms h-96 relative overflow-hidden">
              <a
                :href="GOOGLE_LOCATION_LINK"
                target="_blank"
                class="h-full"
                rel="noopener noreferrer"
              >
                <div
                  class="bg-white bg-opacity-50 z-10 relative text-gray-700 text-center"
                >
                  <h3>Localização da Chelevi</h3>
                  <p class="font-medium">
                    Clique na imagem para abrir a localização no google maps
                  </p>
                </div>
                <img
                  class="absolute h-full w-full object-cover top-0"
                  src="~/assets/images/map.png"
                  alt=""
                />
              </a>
            </section>
          </div>
        </div>
        <div class="row topmargin_40">
          <div class="col-sm-4">
            <div class="teaser text-center">
              <div class="teaser_icon highlight size_normal">
                <i class="rt-icon2-phone5"></i>
              </div>
              <p>
                <span class="grey">Telefone:</span>{{ PHONE_CALL }}<br />
                <span class="grey">Whatsapp:</span>{{ PHONE_CALL }}
              </p>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="teaser text-center">
              <div class="teaser_icon highlight size_normal">
                <i class="rt-icon2-location2"></i>
              </div>
              <p>
                {{ LOCATION_TEXT }}<br />
                Maputo Cidade, Moçambique
              </p>
            </div>
          </div>
          <div class="col-sm-4">
            <div class="teaser text-center">
              <div class="teaser_icon highlight size_normal">
                <i class="rt-icon2-mail"></i>
              </div>
              <p>{{ EMAIL_LINK }}</p>
            </div>
          </div>
        </div>
        <div class="row topmargin_40">
          <div class="col-sm-12">
            <form class="contact-form" method="post" action="./">
              <div class="row">
                <div class="col-sm-6">
                  <p class="form-group">
                    <label for="name"
                      >Nome completo <span class="required">*</span></label
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
                      placeholder="Nome completo"
                    />
                  </p>
                  <p class="form-group">
                    <label for="email"
                      >Email<span class="required">*</span></label
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
                      placeholder="Email"
                    />
                  </p>
                  <p class="form-group">
                    <label for="subject"
                      >Assunto<span class="required">*</span></label
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
                      placeholder="Assunto"
                    />
                  </p>
                </div>
                <div class="col-sm-6">
                  <p class="contact-form-message form-group">
                    <label for="message">Mensagem</label>
                    <i class="fa fa-comment highlight" aria-hidden="true"></i>
                    <textarea
                      id="message"
                      aria-required="true"
                      rows="7"
                      cols="45"
                      name="message"
                      class="form-control"
                      placeholder="Mensagem"
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
                      Enviar mensagem
                    </button>
                  </p>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
    <news-letter />
    <gallery-scroll />
  </main>
</template>
<script>
import BreadcrumbItem from '../components/breadcrumbItem.vue'
import NewsLetter from '../components/newsLetter.vue'
import {
  GOOGLE_LOCATION_LINK,
  EMAIL_LINK,
  PHONE_CALL,
  WHATSAPP_LINK_URL,
  LOCATION_TEXT,
} from '@/constants'
import GalleryScroll from '@/components/galleryScroll.vue'
export default {
  components: {
    GalleryScroll,
    BreadcrumbItem,
    NewsLetter,
  },
  data: function () {
    return {
      GOOGLE_LOCATION_LINK,
      EMAIL_LINK,
      PHONE_CALL,
      WHATSAPP_LINK_URL,
      LOCATION_TEXT,
    }
  },
}
</script>
