<template>
  <div>
    <div id="canvas">
      <div id="box_wrapper">
        <!-- template sections -->
        <header class="page_header header_white header_v1 toggler_xxs_right">
          <div class="container-fluid">
            <div class="row">
              <div class="col-sm-12 display-flex v-center">
                <div class="header_left_logo">
                  <a href="./" class="logo">
                    <img src="~/assets/images/logo.png" alt="" />
                  </a>
                </div>
                <div class="header_mainmenu text-center">
                  <!-- main nav start -->
                  <nav class="mainmenu_wrapper">
                    <ul class="mainmenu nav sf-menu">
                      <li><nuxt-link to="/">Home</nuxt-link></li>
                      <li><nuxt-link to="about">Sobre</nuxt-link></li>
                      <li><nuxt-link to="services">Serviços</nuxt-link></li>
                      <li><nuxt-link to="events">Eventos</nuxt-link></li>
                      <li><nuxt-link to="blog">Blog</nuxt-link></li>
                      <li>
                        <nuxt-link to="gallery-tile">Galeria</nuxt-link>
                      </li>
                      <li><nuxt-link to="shop">Shop</nuxt-link></li>
                      <li><nuxt-link to="contact">Contactos</nuxt-link></li>
                    </ul>
                  </nav>
                  <!-- eof main nav -->
                  <!-- header toggler --><span class="toggle_menu"
                    ><span></span
                  ></span>
                </div>
                <div class="header_right_buttons text-right">
                  <ul class="inline-dropdown inline-block">
                    <li class="dropdown login-dropdown">
                      <a
                        id="login"
                        data-target="#"
                        href="./"
                        data-toggle="dropdown"
                        aria-haspopup="true"
                        role="button"
                        aria-expanded="false"
                        class="theme_button small_button round_button bg_button margin_0"
                      >
                        <i class="qtyler-user" aria-hidden="true"></i>
                      </a>
                      <div
                        class="dropdown-menu small-text darklinks"
                        aria-labelledby="login"
                      >
                        <strong class="grey">currency</strong><br />
                        <a href="#" class="active">usd</a><br />
                        <a href="#">eur</a><br />
                        <a href="#">gbp</a>
                        <hr />
                        <strong class="grey">My Account</strong><br />
                        <a href="#">log in</a><br />
                        <a href="#">register</a>
                      </div>
                    </li>
                    <li class="dropdown cart-dropdown">
                      <a
                        id="cart"
                        data-target="#"
                        href="./"
                        data-toggle="dropdown"
                        aria-haspopup="true"
                        role="button"
                        aria-expanded="false"
                        class="theme_button small_button round_button bg_button margin_0"
                      >
                        <i class="qtyler-shop-bag" aria-hidden="true"></i>

                        <span class="count">3</span>
                      </a>
                      <div class="dropdown-menu" aria-labelledby="cart">
                        <div class="widget widget_shopping_cart">
                          <div class="widget_shopping_cart_content">
                            <ul class="cart_list product_list_widget">
                              <li class="media">
                                <div class="media-left media-middle">
                                  <a href="shop-product">
                                    <img
                                      src="~/assets/images/shop/03.jpg"
                                      alt=""
                                    />
                                  </a>
                                </div>
                                <div class="media-body media-middle">
                                  <a
                                    href="#"
                                    class="remove"
                                    title="Remove this item"
                                  ></a>
                                  <p class="darklinks">
                                    <a href="shop-product"
                                      >Heather grey pullover</a
                                    >
                                  </p>
                                  <span class="product-quantity">
                                    <span class="price">$29.95</span>
                                    <span>x 1</span>
                                  </span>
                                </div>
                              </li>
                              <li class="media">
                                <div class="media-left media-middle">
                                  <a href="shop-product">
                                    <img
                                      src="~/assets/images/shop/05.jpg"
                                      alt=""
                                    />
                                  </a>
                                </div>
                                <div class="media-body media-middle">
                                  <a
                                    href="#"
                                    class="remove"
                                    title="Remove this item"
                                  ></a>
                                  <p class="darklinks">
                                    <a href="shop-product">Slim short dress</a>
                                  </p>
                                  <span class="product-quantity">
                                    <span class="price">$34.95</span>
                                    <span>x 2</span>
                                  </span>
                                </div>
                              </li>
                            </ul>
                            <p class="total grey">
                              <span>Subtotal:</span>
                              <span class="price">$69.94</span>
                            </p>
                            <p class="buttons">
                              <a href="shop-cart" class="theme_button"
                                >View cart</a
                              >
                              <a href="shop-cart" class="theme_button color1"
                                >Checkout</a
                              >
                            </p>
                          </div>
                        </div>
                      </div>
                    </li>
                    <li class="dropdown social-dropdown">
                      <a
                        id="social"
                        data-target="#"
                        href="./"
                        data-toggle="dropdown"
                        aria-haspopup="true"
                        role="button"
                        aria-expanded="false"
                        class="theme_button small_button round_button bg_button margin_0"
                      >
                        <i class="qtyler-share" aria-hidden="true"></i>
                      </a>
                      <div class="dropdown-menu">
                        <a
                          class="social-icon socicon-facebook dark-icon"
                          href="#"
                          title="Facebook"
                        ></a>
                        <a
                          class="social-icon socicon-googleplus dark-icon"
                          href="#"
                          title="Twitter"
                        ></a>
                        <a
                          class="social-icon socicon-instagram dark-icon"
                          href="#"
                          title="Instagram"
                        ></a>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
        </header>
        <Nuxt />
        <footer
          class="page_footer ls section_padding_top_150 section_padding_bottom_140 columns_margin_bottom_30"
        >
          <div class="mt-16">
            <div class="row">
              <div class="col-xs-12 col-md-4 text-center text-md-left">
                <div class="widget widget_text">
                  <div class="logo">
                    <img src="~/assets/images/logo.png" alt="" />
                  </div>
                  <ul class="list-unstyled greylinks">
                    <li>
                      <div class="media small-media">
                        <div class="media-left">
                          <i class="qtyler-phone"></i>
                        </div>
                        <div class="media-body">{{ PHONE_CALL }}</div>
                      </div>
                    </li>
                    <li>
                      <div class="media small-media">
                        <div class="media-left">
                          <i class="qtyler-envelope"></i>
                        </div>
                        <div class="media-body">
                          <a :href="`mailto:`">{{ EMAIL_LINK }}</a>
                        </div>
                      </div>
                    </li>
                    <li>
                      <div class="media small-media">
                        <div class="media-left">
                          <i class="qtyler-map-marker"></i>
                        </div>
                        <div class="media-body">{{ LOCATION_TEXT }}</div>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
              <div class="col-xs-12 col-sm-6 col-md-4 text-center text-md-left">
                <div class="widget widget_text">
                  <h3 class="widget-title">Horário</h3>
                  <ul class="feature-list">
                    <li>
                      <span>Meio de semana</span> <span>8:00 - 20:00</span>
                    </li>
                    <li><span>Sábado</span> <span>9:00 - 16:00</span></li>
                    <li><span>Domingo</span> <span>Closed</span></li>
                    <li><span>Feriados</span> <span>10:00 - 14:00</span></li>
                  </ul>
                </div>
              </div>
              <div class="col-xs-12 col-sm-6 col-md-4 text-center text-md-left">
                <div class="widget widget_text">
                  <h3 class="widget-title">Detalhes</h3>
                  <ul class="list-unstyled greylinks">
                    <li>
                      <div class="media small-media">
                        <div class="media-left">
                          <i class="qtyler-delivery"></i>
                        </div>
                        <div class="media-body">
                          Entregamos em todo moçambique
                        </div>
                      </div>
                    </li>
                    <li>
                      <div class="media small-media">
                        <div class="media-left">
                          <i class="qtyler-headphones"></i>
                        </div>
                        <div class="media-body">
                          Atendimento ao cliente rápido e excelente
                        </div>
                      </div>
                    </li>
                    <li>
                      <div class="media small-media">
                        <div class="media-left">
                          <i class="qtyler-money"></i>
                        </div>
                        <div class="media-body">
                          aceitamos Devoluções mediante condições
                        </div>
                      </div>
                    </li>
                  </ul>
                </div>
              </div>
            </div>
          </div>
          <section class="mb-8">
            <div class="flex justify-center">
              <img class="w-48" src="~/assets/images/logo.png" alt="" />
            </div>
          </section>
        </footer>
      </div>
    </div>
  </div>
</template>

<script>
import { PHONE_CALL, EMAIL_LINK, LOCATION_TEXT } from '@/constants'
export default {
  data: function () {
    return {
      PHONE_CALL,
      EMAIL_LINK,
      LOCATION_TEXT,
    }
  },
}
</script>
