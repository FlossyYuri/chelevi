<template>
  <main>
    <main-carrousel />
    <our-textiles />
    <section id="products" class="ls fluid_padding_0 columns_padding_0">
      <div class="container-fluid">
        <div class="row">
          <div class="col-xs-12 text-center">
            <h2 class="section_header">Os nossos tecidos</h2>
            <div class="filters carousel_filters">
              <a href="#" data-filter="*">Todos</a>
              <a href="#" data-filter=".men">Homem</a>
              <a href="#" data-filter=".women">Mulher</a>
              <a href="#" data-filter=".kids">Crianças</a>
            </div>
            <div
              class="owl-carousel products-carousel gallery-carousel"
              data-nav="true"
              data-dots="false"
              data-responsive-xlg="5"
              data-responsive-sm="3"
              data-responsive-xs="2"
              data-responsive-xxs="1"
              data-filters=".carousel_filters"
              data-margin="30"
            >
              <article
                class="product vertical-item text-center with-corner-label men"
              >
                <div class="item-media-wrap bottommargin_25">
                  <div class="item-media">
                    <a href="shop-product">
                      <img src="~/assets/images/shop/01.jpg" alt="" />
                      <img src="~/assets/images/shop/01-1.jpg" alt="" />
                    </a>
                    <div class="product_buttons darklinks">
                      <a
                        href="#"
                        class="add_to_cart"
                        data-toggle="tooltip"
                        title="Adicionar ao carrinho"
                      >
                        <i class="qtyler-shop-bag"></i>
                        <span class="sr-only">Adicionar ao carrinho</span>
                      </a>
                      <a
                        href=""
                        class="add_to_wishlist"
                        data-toggle="tooltip"
                        title="Adicionar a Wishlist"
                      >
                        <i class="qtyler-heart"></i>
                        <span class="sr-only">Adicionar a Wishlist</span>
                      </a>
                      <a
                        class="p-view prettyPhoto"
                        data-gal="prettyPhoto[product1-gal]"
                        href="~/assets/images/shop/01.jpg"
                        data-toggle="tooltip"
                        title="Expandir foto"
                      >
                        <i class="qtyler-external"></i>
                        <span class="sr-only">Expandir foto</span>
                      </a>
                      <a
                        class="p-view prettyPhoto sr-only"
                        title=""
                        data-gal="prettyPhoto[product1-gal]"
                        href="~/assets/images/shop/01-1.jpg"
                      ></a>
                    </div>
                  </div>
                  <div class="corner-label hot">Quente</div>
                </div>
                <div class="item-content">
                  <h3 class="entry-title">
                    <a href="shop-product">Blusa branca</a>
                  </h3>
                  <div class="price"><span class="amount">1.200 MZN</span></div>
                </div>
              </article>
              <article class="product vertical-item text-center men">
                <div class="item-media-wrap bottommargin_25">
                  <div class="item-media">
                    <a href="shop-product">
                      <img src="~/assets/images/shop/02.jpg" alt="" />
                      <img src="~/assets/images/shop/02-1.jpg" alt="" />
                    </a>
                    <div class="product_buttons darklinks">
                      <a
                        href="#"
                        class="add_to_cart"
                        data-toggle="tooltip"
                        title="Adicionar ao carrinho"
                      >
                        <i class="qtyler-shop-bag"></i>
                        <span class="sr-only">Adicionar ao carrinho</span>
                      </a>
                      <a
                        href=""
                        class="add_to_wishlist"
                        data-toggle="tooltip"
                        title="Adicionar a Wishlist"
                      >
                        <i class="qtyler-heart"></i>
                        <span class="sr-only">Adicionar a Wishlist</span>
                      </a>
                      <a
                        class="p-view prettyPhoto"
                        data-gal="prettyPhoto[product2-gal]"
                        href="~/assets/images/shop/02.jpg"
                        data-toggle="tooltip"
                        title="Expandir foto"
                      >
                        <i class="qtyler-external"></i>
                        <span class="sr-only">Expandir foto</span>
                      </a>
                      <a
                        class="p-view prettyPhoto sr-only"
                        title=""
                        data-gal="prettyPhoto[product2-gal]"
                        href="~/assets/images/shop/02-1.jpg"
                      ></a>
                    </div>
                  </div>
                </div>
                <div class="item-content">
                  <h3 class="entry-title">
                    <a href="shop-product">Camiseta preta lisa </a>
                  </h3>
                  <div class="price"><span class="amount">1.500 MZN</span></div>
                </div>
              </article>
              <article
                class="product vertical-item text-center with-corner-label women"
              >
                <div class="item-media-wrap bottommargin_25">
                  <div class="item-media">
                    <a href="shop-product">
                      <img src="~/assets/images/shop/03.jpg" alt="" />
                      <img src="~/assets/images/shop/03-1.jpg" alt="" />
                    </a>
                    <div class="product_buttons darklinks">
                      <a
                        href="#"
                        class="add_to_cart"
                        data-toggle="tooltip"
                        title="Adicionar ao carrinho"
                      >
                        <i class="qtyler-shop-bag"></i>
                        <span class="sr-only">Adicionar ao carrinho</span>
                      </a>
                      <a
                        href=""
                        class="add_to_wishlist"
                        data-toggle="tooltip"
                        title="Adicionar a Wishlist"
                      >
                        <i class="qtyler-heart"></i>
                        <span class="sr-only">Adicionar a Wishlist</span>
                      </a>
                      <a
                        class="p-view prettyPhoto"
                        data-gal="prettyPhoto[product3-gal]"
                        href="~/assets/images/shop/03.jpg"
                        data-toggle="tooltip"
                        title="Expandir foto"
                      >
                        <i class="qtyler-external"></i>
                        <span class="sr-only">Expandir foto</span>
                      </a>
                      <a
                        class="p-view prettyPhoto sr-only"
                        title=""
                        data-gal="prettyPhoto[product3-gal]"
                        href="~/assets/images/shop/03-1.jpg"
                      ></a>
                    </div>
                  </div>
                  <div class="corner-label sale">sale</div>
                </div>
                <div class="item-content">
                  <h3 class="entry-title">
                    <a href="shop-product">Vestido florido</a>
                  </h3>
                  <div class="price"><span class="amount">3.200 MZN</span></div>
                </div>
              </article>
              <article class="product vertical-item text-center women">
                <div class="item-media-wrap bottommargin_25">
                  <div class="item-media">
                    <a href="shop-product">
                      <img src="~/assets/images/shop/04.jpg" alt="" />
                      <img src="~/assets/images/shop/04-1.jpg" alt="" />
                    </a>
                    <div class="product_buttons darklinks">
                      <a
                        href="#"
                        class="add_to_cart"
                        data-toggle="tooltip"
                        title="Adicionar ao carrinho"
                      >
                        <i class="qtyler-shop-bag"></i>
                        <span class="sr-only">Adicionar ao carrinho</span>
                      </a>
                      <a
                        href=""
                        class="add_to_wishlist"
                        data-toggle="tooltip"
                        title="Adicionar a Wishlist"
                      >
                        <i class="qtyler-heart"></i>
                        <span class="sr-only">Adicionar a Wishlist</span>
                      </a>
                      <a
                        class="p-view prettyPhoto"
                        data-gal="prettyPhoto[product4-gal]"
                        href="~/assets/images/shop/04.jpg"
                        data-toggle="tooltip"
                        title="Expandir foto"
                      >
                        <i class="qtyler-external"></i>
                        <span class="sr-only">Expandir foto</span>
                      </a>
                      <a
                        class="p-view prettyPhoto sr-only"
                        title=""
                        data-gal="prettyPhoto[product4-gal]"
                        href="~/assets/images/shop/04-1.jpg"
                      ></a>
                    </div>
                  </div>
                </div>
                <div class="item-content">
                  <h3 class="entry-title">
                    <a href="shop-product">Saia jeans curta</a>
                  </h3>
                  <div class="price"><span class="amount">1.300 MZN</span></div>
                </div>
              </article>
              <article
                class="product vertical-item text-center with-corner-label women"
              >
                <div class="item-media-wrap bottommargin_25">
                  <div class="item-media">
                    <a href="shop-product">
                      <img src="~/assets/images/shop/05.jpg" alt="" />
                      <img src="~/assets/images/shop/05-1.jpg" alt="" />
                    </a>
                    <div class="product_buttons darklinks">
                      <a
                        href="#"
                        class="add_to_cart"
                        data-toggle="tooltip"
                        title="Adicionar ao carrinho"
                      >
                        <i class="qtyler-shop-bag"></i>
                        <span class="sr-only">Adicionar ao carrinho</span>
                      </a>
                      <a
                        href=""
                        class="add_to_wishlist"
                        data-toggle="tooltip"
                        title="Adicionar a Wishlist"
                      >
                        <i class="qtyler-heart"></i>
                        <span class="sr-only">Adicionar a Wishlist</span>
                      </a>
                      <a
                        class="p-view prettyPhoto"
                        data-gal="prettyPhoto[product5-gal]"
                        href="~/assets/images/shop/05.jpg"
                        data-toggle="tooltip"
                        title="Expandir foto"
                      >
                        <i class="qtyler-external"></i>
                        <span class="sr-only">Expandir foto</span>
                      </a>
                      <a
                        class="p-view prettyPhoto sr-only"
                        title=""
                        data-gal="prettyPhoto[product5-gal]"
                        href="~/assets/images/shop/05-1.jpg"
                      ></a>
                    </div>
                  </div>
                  <div class="corner-label new">new</div>
                </div>
                <div class="item-content">
                  <h3 class="entry-title">
                    <a href="shop-product">Calça social preta</a>
                  </h3>
                  <div class="price"><span class="amount">2.500 MZN</span></div>
                </div>
              </article>
              <article
                class="product vertical-item text-center with-corner-label women"
              >
                <div class="item-media-wrap bottommargin_25">
                  <div class="item-media">
                    <a href="shop-product">
                      <img src="~/assets/images/shop/06.jpg" alt="" />
                      <img src="~/assets/images/shop/06-1.jpg" alt="" />
                    </a>
                    <div class="product_buttons darklinks">
                      <a
                        href="#"
                        class="add_to_cart"
                        data-toggle="tooltip"
                        title="Adicionar ao carrinho"
                      >
                        <i class="qtyler-shop-bag"></i>
                        <span class="sr-only">Adicionar ao carrinho</span>
                      </a>
                      <a
                        href=""
                        class="add_to_wishlist"
                        data-toggle="tooltip"
                        title="Adicionar a Wishlist"
                      >
                        <i class="qtyler-heart"></i>
                        <span class="sr-only">Adicionar a Wishlist</span>
                      </a>
                      <a
                        class="p-view prettyPhoto"
                        data-gal="prettyPhoto[product6-gal]"
                        href="~/assets/images/shop/06.jpg"
                        data-toggle="tooltip"
                        title="Expandir foto"
                      >
                        <i class="qtyler-external"></i>
                        <span class="sr-only">Expandir foto</span>
                      </a>
                      <a
                        class="p-view prettyPhoto sr-only"
                        title=""
                        data-gal="prettyPhoto[product6-gal]"
                        href="~/assets/images/shop/06-1.jpg"
                      ></a>
                    </div>
                  </div>
                  <div class="corner-label hot">Quente</div>
                </div>
                <div class="item-content">
                  <h3 class="entry-title">
                    <a href="shop-product">Shorts jeans</a>
                  </h3>
                  <div class="price"><span class="amount">1.100 MZN</span></div>
                </div>
              </article>
              <article class="product vertical-item text-center women">
                <div class="item-media-wrap bottommargin_25">
                  <div class="item-media">
                    <a href="shop-product">
                      <img src="~/assets/images/shop/07.jpg" alt="" />
                      <img src="~/assets/images/shop/07-1.jpg" alt="" />
                    </a>
                    <div class="product_buttons darklinks">
                      <a
                        href="#"
                        class="add_to_cart"
                        data-toggle="tooltip"
                        title="Adicionar ao carrinho"
                      >
                        <i class="qtyler-shop-bag"></i>
                        <span class="sr-only">Adicionar ao carrinho</span>
                      </a>
                      <a
                        href=""
                        class="add_to_wishlist"
                        data-toggle="tooltip"
                        title="Adicionar a Wishlist"
                      >
                        <i class="qtyler-heart"></i>
                        <span class="sr-only">Adicionar a Wishlist</span>
                      </a>
                      <a
                        class="p-view prettyPhoto"
                        data-gal="prettyPhoto[product7-gal]"
                        href="~/assets/images/shop/07.jpg"
                        data-toggle="tooltip"
                        title="Expandir foto"
                      >
                        <i class="qtyler-external"></i>
                        <span class="sr-only">Expandir foto</span>
                      </a>
                      <a
                        class="p-view prettyPhoto sr-only"
                        title=""
                        data-gal="prettyPhoto[product7-gal]"
                        href="~/assets/images/shop/07-1.jpg"
                      ></a>
                    </div>
                  </div>
                </div>
                <div class="item-content">
                  <h3 class="entry-title">
                    <a href="shop-product">Blusa listrada</a>
                  </h3>
                  <div class="price"><span class="amount">1.800 MZN</span></div>
                </div>
              </article>
              <article
                class="product vertical-item text-center with-corner-label men"
              >
                <div class="item-media-wrap bottommargin_25">
                  <div class="item-media">
                    <a href="shop-product">
                      <img src="~/assets/images/shop/08.jpg" alt="" />
                      <img src="~/assets/images/shop/08-1.jpg" alt="" />
                    </a>
                    <div class="product_buttons darklinks">
                      <a
                        href="#"
                        class="add_to_cart"
                        data-toggle="tooltip"
                        title="Adicionar ao carrinho"
                      >
                        <i class="qtyler-shop-bag"></i>
                        <span class="sr-only">Adicionar ao carrinho</span>
                      </a>
                      <a
                        href=""
                        class="add_to_wishlist"
                        data-toggle="tooltip"
                        title="Adicionar a Wishlist"
                      >
                        <i class="qtyler-heart"></i>
                        <span class="sr-only">Adicionar a Wishlist</span>
                      </a>
                      <a
                        class="p-view prettyPhoto"
                        data-gal="prettyPhoto[product8-gal]"
                        href="~/assets/images/shop/08.jpg"
                        data-toggle="tooltip"
                        title="Expandir foto"
                      >
                        <i class="qtyler-external"></i>
                        <span class="sr-only">Expandir foto</span>
                      </a>
                      <a
                        class="p-view prettyPhoto sr-only"
                        title=""
                        data-gal="prettyPhoto[product8-gal]"
                        href="~/assets/images/shop/08-1.jpg"
                      ></a>
                    </div>
                  </div>
                  <div class="corner-label sale">sale</div>
                </div>
                <div class="item-content">
                  <h3 class="entry-title">
                    <a href="shop-product">Jaqueta de couro marrom</a>
                  </h3>
                  <div class="price"><span class="amount">4.200 MZN</span></div>
                </div>
              </article>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section
      id="contact-form"
      class="ls section_padding_top_150 section_padding_bottom_150 bottommargin_60"
    >
      <div class="container">
        <div class="row flex-wrap v-center">
          <div class="col-xs-12 col-md-5 col-md-push-6">
            <img
              src="~/assets/images/tailoring.jpg"
              alt=""
              class="contact-form-cover"
            />
          </div>
          <div class="col-xs-12 col-md-7 col-md-pull-5">
            <h2 class="section_header">Alfaiataria personalizada</h2>
            <p class="small-text grey">com a melhor qualidade</p>
            <div class="toppadding_5"></div>
            <form
              class="contact-form row columns_padding_10"
              method="post"
              action="./"
            >
              <div class="col-xs-12">
                <div class="form-group">
                  <input
                    id="name"
                    type="text"
                    aria-required="true"
                    size="30"
                    value=""
                    name="name"
                    class="form-control with_icon"
                    placeholder="Seu nome"
                  />
                  <i class="qtyler-user grey"></i>
                </div>
              </div>
              <div class="col-xs-12 col-sm-6">
                <div class="form-group">
                  <input
                    id="email"
                    type="email"
                    aria-required="true"
                    size="30"
                    value=""
                    name="email"
                    class="form-control with_icon"
                    placeholder="Email"
                  />
                  <i class="qtyler-envelope grey"></i>
                </div>
              </div>
              <div class="col-xs-12 col-sm-6">
                <div class="form-group">
                  <input
                    id="phone"
                    type="tel"
                    size="30"
                    value=""
                    name="phone"
                    class="form-control with_icon"
                    placeholder="Celular"
                  />
                  <i class="qtyler-phone grey"></i>
                </div>
              </div>
              <div class="col-xs-12">
                <div class="form-group">
                  <textarea
                    id="message"
                    aria-required="true"
                    rows="3"
                    cols="45"
                    name="message"
                    class="form-control with_icon"
                    placeholder="Messagem"
                  ></textarea>
                  <i class="qtyler-comment grey"></i>
                </div>
              </div>
              <div class="col-xs-12 bottommargin_0">
                <div class="contact-form-submit">
                  <button
                    id="contact_form_submit"
                    type="submit"
                    name="contact_submit"
                    class="theme_button min_width_button margin_0"
                  >
                    Encomendar
                  </button>
                </div>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
    <section
      id="testimonials"
      class="ls ms parallax overlay_color section_padding_top_150 section_padding_bottom_150"
    >
      <div class="container">
        <div class="row">
          <div class="col-xs-12 text-center">
            <div
              class="owl-carousel"
              data-responsive-lg="1"
              data-responsive-md="1"
              data-responsive-sm="1"
              data-dots="true"
              data-nav="true"
            >
              <blockquote>
                <div class="avatar">
                  <img src="~/assets/images/faces/01.jpg" alt="" />
                </div>
                <p>
                  Eu sou fã do Chelevi há anos. A equipe é super atenciosa e as
                  roupas são sempre de alta qualidade. Eu amo como as peças são
                  exclusivas e diferentes de tudo o que encontro em outras
                  lojas.
                </p>
                <cite>Ana Santos</cite>
              </blockquote>
              <blockquote>
                <div class="avatar">
                  <img src="~/assets/images/faces/02.jpg" alt="" />
                </div>
                <p>
                  Eu amo as roupas do Chelevi! A qualidade dos tecidos é
                  incrível e as peças são tão elegantes. Eu sempre recebo
                  elogios quando uso algo do Chelevi. Definitivamente recomendo!
                </p>
                <cite>Maria Silva</cite>
              </blockquote>
              <blockquote>
                <div class="avatar">
                  <img src="~/assets/images/faces/03.jpg" alt="" />
                </div>
                <p>
                  Eu comprei um vestido no Chelevi para um casamento e foi a
                  melhor escolha que eu poderia ter feito. O vestido era lindo e
                  feito com um tecido tão macio e confortável. Eu me senti tão
                  confiante e elegante naquele dia. Obrigada, Chelevi!
                </p>
                <cite>Joana Oliveira</cite>
              </blockquote>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section
      id="blog"
      class="ls section_padding_top_150 section_padding_bottom_150"
    >
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            <h2 class="section_header text-center">News &amp; Events</h2>
            <p class="small-text grey">our blogs</p>
            <div class="row columns_margin_bottom_20">
              <div class="isotope-item col-xs-12 col-md-6">
                <article class="vertical-item content-absolute content-caption">
                  <div class="item-media">
                    <a href="blog-single-right">
                      <img src="~/assets/images/blog-square/01.jpg" alt="" />
                    </a>
                    <div class="entry-meta-corner">
                      <a href="blog-single-left">
                        <time datetime="2017-10-03T08:50:40+00:00">20 jun</time>
                      </a>
                    </div>
                  </div>
                  <div class="item-content ls">
                    <h3 class="entry-title small">
                      <a href="blog-single-right"
                        >Ferragamo: Bringing the French Riviera to Italian
                        menswear</a
                      >
                    </h3>
                  </div>
                </article>
              </div>
              <div class="col-xs-12 col-sm-6">
                <article class="side-item side-md">
                  <div class="row v-center">
                    <div class="col-xs-12 col-md-6">
                      <div class="item-media">
                        <a href="blog-single-right">
                          <img
                            src="~/assets/images/blog-square/02.jpg"
                            alt=""
                          />
                        </a>
                      </div>
                    </div>
                    <div class="col-xs-12 col-md-6">
                      <div class="item-content">
                        <div class="entry-meta small-text greylinks">
                          <span class="date">
                            <a href="blog-single-left">
                              <time datetime="2017-10-03T08:50:40+00:00"
                                >19 jun</time
                              >
                            </a>
                          </span>
                        </div>
                        <h3 class="entry-title small">
                          <a href="blog-single-right"
                            >Bold and beautiful: Gustav Klimt inspires Turnbull
                            & Asser</a
                          >
                        </h3>
                        <a href="blog-single-right" class="more-link">more</a>
                      </div>
                    </div>
                  </div>
                </article>
              </div>
              <div class="col-xs-12 col-sm-6">
                <article class="side-item side-md">
                  <div class="row v-center">
                    <div class="col-xs-12 col-md-6">
                      <div class="item-media">
                        <a href="blog-single-right">
                          <img
                            src="~/assets/images/blog-square/03.jpg"
                            alt=""
                          />
                        </a>
                      </div>
                    </div>
                    <div class="col-xs-12 col-md-6">
                      <div class="item-content">
                        <div class="entry-meta small-text greylinks">
                          <span class="date">
                            <a href="blog-single-left">
                              <time datetime="2017-10-03T08:50:40+00:00"
                                >15 jun</time
                              >
                            </a>
                          </span>
                        </div>
                        <h3 class="entry-title small">
                          <a href="blog-single-right"
                            >The middle ground of modern menswear at Hardy
                            Amies</a
                          >
                        </h3>
                        <a href="blog-single-right" class="more-link">more</a>
                      </div>
                    </div>
                  </div>
                </article>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <section
      id="section-social"
      class="ls with_top_border columns_margin_0 topmargin_80"
    >
      <div class="container">
        <div class="row">
          <div class="col-xs-12 text-center">
            <div class="page_social">
              <a
                class="social-icon socicon-facebook dark-icon"
                :href="FACEBOOK_URL"
                title="Facebook"
              ></a>
              <a
                class="social-icon socicon-whatsapp dark-icon"
                :href="WHATSAPP_LINK_URL"
                title="Whatsapp"
              ></a>
              <a
                class="social-icon socicon-instagram dark-icon"
                :href="INSTAGRAM_URL"
                title="Instagram"
              ></a>
              <a
                class="social-icon socicon-telegram dark-icon"
                :href="TELEGRAM_URL"
                title="Telegram"
              ></a>
              <a
                class="social-icon socicon-mail dark-icon"
                :href="`mailto:${EMAIL_LINK}`"
                title="Email"
              ></a>
              <a
                class="social-icon socicon-viber dark-icon"
                :href="`tel:${PHONE_CALL}`"
                title="Chamada"
              ></a>
            </div>
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
    <gallery-scroll />
  </main>
</template>
<script>
import {
  EMAIL_LINK,
  FACEBOOK_URL,
  INSTAGRAM_URL,
  PHONE_CALL,
  TELEGRAM_URL,
  WHATSAPP_LINK_URL,
} from '@/constants'
import GalleryScroll from '@/components/galleryScroll.vue'
import MainCarrousel from '@/components/mainCarrousel.vue'
import OurTextiles from '@/components/OurTextiles.vue'
export default {
  components: {
    GalleryScroll,
    MainCarrousel,
    OurTextiles,
  },
  data: function () {
    return {
      EMAIL_LINK,
      FACEBOOK_URL,
      INSTAGRAM_URL,
      PHONE_CALL,
      TELEGRAM_URL,
      WHATSAPP_LINK_URL,
    }
  },
}
</script>
