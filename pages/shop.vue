<template>
  <main>
    <breadcrumb-item title="Shop" uri="Products" />
    <section
      class="ls section_padding_top_150 section_padding_bottom_150 columns_padding_30"
    >
      <div class="container">
        <div class="row">
          <div class="col-xs-12 col-md-9 col-lg-9 col-md-push-3 col-lg-push-3">
            <div class="shop-sorting">
              <form class="content-justify v-center v-spacing content-margins">
                <div>Showing 1-6 of 36 results</div>
                <div class="form-group">
                  <select id="date" aria-required="true" name="date">
                    <option value="">Sort by</option>
                    <option value="default">Default Sorting</option>
                    <option value="value">by Value</option>
                    <option value="date">by Date</option>
                    <option value="popular">by Popularity</option>
                  </select>
                </div>
              </form>
            </div>
            <div class="columns-3">
              <ul id="products" class="products list-unstyled">
                <li class="product type-product">
                  <article
                    class="vertical-item text-center with-corner-label men"
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
                        <a href="shop-product">Black tank top</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$24.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article class="vertical-item text-center men">
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
                        <a href="shop-product">White pullover</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$19.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article
                    class="vertical-item text-center with-corner-label women"
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
                        <a href="shop-product">Heather grey pullover</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$29.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article class="vertical-item text-center women">
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
                        <a href="shop-product">White sport bra</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$14.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article
                    class="vertical-item text-center with-corner-label women"
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
                        <a href="shop-product">Slim short dress</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$34.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article
                    class="vertical-item text-center with-corner-label women"
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
                        <a href="shop-product">Black t-shirt</a>
                      </h3>
                      <div class="price"><span class="amount">$9.95</span></div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article class="vertical-item text-center women">
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
                        <a href="shop-product"
                          >Heather grey long sleeve crop top</a
                        >
                      </h3>
                      <div class="price">
                        <span class="amount">$19.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article
                    class="vertical-item text-center with-corner-label men"
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
                        <a href="shop-product">Heather grey hoodie</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$19.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article class="vertical-item text-center men">
                    <div class="item-media-wrap bottommargin_25">
                      <div class="item-media">
                        <a href="shop-product">
                          <img src="~/assets/images/shop/09.jpg" alt="" />
                          <img src="~/assets/images/shop/09-1.jpg" alt="" />
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
                            data-gal="prettyPhoto[product9-gal]"
                            href="~/assets/images/shop/09.jpg"
                            data-toggle="tooltip"
                            title="Expandir foto"
                          >
                            <i class="qtyler-external"></i>
                            <span class="sr-only">Expandir foto</span>
                          </a>
                          <a
                            class="p-view prettyPhoto sr-only"
                            title=""
                            data-gal="prettyPhoto[product9-gal]"
                            href="~/assets/images/shop/09-1.jpg"
                          ></a>
                        </div>
                      </div>
                    </div>
                    <div class="item-content">
                      <h3 class="entry-title">
                        <a href="shop-product">White tucked sleeves t-shirt</a>
                      </h3>
                      <div class="price"><span class="amount">$9.95</span></div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article
                    class="vertical-item text-center with-corner-label women"
                  >
                    <div class="item-media-wrap bottommargin_25">
                      <div class="item-media">
                        <a href="shop-product">
                          <img src="~/assets/images/shop/10.jpg" alt="" />
                          <img src="~/assets/images/shop/10-1.jpg" alt="" />
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
                            data-gal="prettyPhoto[product10-gal]"
                            href="~/assets/images/shop/10.jpg"
                            data-toggle="tooltip"
                            title="Expandir foto"
                          >
                            <i class="qtyler-external"></i>
                            <span class="sr-only">Expandir foto</span>
                          </a>
                          <a
                            class="p-view prettyPhoto sr-only"
                            title=""
                            data-gal="prettyPhoto[product10-gal]"
                            href="~/assets/images/shop/10-1.jpg"
                          ></a>
                        </div>
                      </div>
                      <div class="corner-label new">new</div>
                    </div>
                    <div class="item-content">
                      <h3 class="entry-title">
                        <a href="shop-product">White pullover</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$29.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article
                    class="vertical-item text-center with-corner-label women"
                  >
                    <div class="item-media-wrap bottommargin_25">
                      <div class="item-media">
                        <a href="shop-product">
                          <img src="~/assets/images/shop/11.jpg" alt="" />
                          <img src="~/assets/images/shop/11-1.jpg" alt="" />
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
                            data-gal="prettyPhoto[product11-gal]"
                            href="~/assets/images/shop/11.jpg"
                            data-toggle="tooltip"
                            title="Expandir foto"
                          >
                            <i class="qtyler-external"></i>
                            <span class="sr-only">Expandir foto</span>
                          </a>
                          <a
                            class="p-view prettyPhoto sr-only"
                            title=""
                            data-gal="prettyPhoto[product11-gal]"
                            href="~/assets/images/shop/11-1.jpg"
                          ></a>
                        </div>
                      </div>
                      <div class="corner-label hot">Quente</div>
                    </div>
                    <div class="item-content">
                      <h3 class="entry-title">
                        <a href="shop-product">White tank top</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$30.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article
                    class="vertical-item text-center with-corner-label women"
                  >
                    <div class="item-media-wrap bottommargin_25">
                      <div class="item-media">
                        <a href="shop-product">
                          <img src="~/assets/images/shop/12.jpg" alt="" />
                          <img src="~/assets/images/shop/12-1.jpg" alt="" />
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
                            data-gal="prettyPhoto[product12-gal]"
                            href="~/assets/images/shop/12.jpg"
                            data-toggle="tooltip"
                            title="Expandir foto"
                          >
                            <i class="qtyler-external"></i>
                            <span class="sr-only">Expandir foto</span>
                          </a>
                          <a
                            class="p-view prettyPhoto sr-only"
                            title=""
                            data-gal="prettyPhoto[product12-gal]"
                            href="~/assets/images/shop/12-1.jpg"
                          ></a>
                        </div>
                      </div>
                      <div class="corner-label new">new</div>
                    </div>
                    <div class="item-content">
                      <h3 class="entry-title">
                        <a href="shop-product">Black t-shirt wide neck</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$15.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article class="vertical-item text-center women">
                    <div class="item-media-wrap bottommargin_25">
                      <div class="item-media">
                        <a href="shop-product">
                          <img src="~/assets/images/shop/13.jpg" alt="" />
                          <img src="~/assets/images/shop/13-1.jpg" alt="" />
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
                            data-gal="prettyPhoto[product10-gal]"
                            href="~/assets/images/shop/13.jpg"
                            data-toggle="tooltip"
                            title="Expandir foto"
                          >
                            <i class="qtyler-external"></i>
                            <span class="sr-only">Expandir foto</span>
                          </a>
                          <a
                            class="p-view prettyPhoto sr-only"
                            title=""
                            data-gal="prettyPhoto[product13-gal]"
                            href="~/assets/images/shop/13-1.jpg"
                          ></a>
                        </div>
                      </div>
                    </div>
                    <div class="item-content">
                      <h3 class="entry-title">
                        <a href="shop-product">White hoodie</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$19.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article
                    class="vertical-item text-center with-corner-label women"
                  >
                    <div class="item-media-wrap bottommargin_25">
                      <div class="item-media">
                        <a href="shop-product">
                          <img src="~/assets/images/shop/14.jpg" alt="" />
                          <img src="~/assets/images/shop/14-1.jpg" alt="" />
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
                            data-gal="prettyPhoto[product14-gal]"
                            href="~/assets/images/shop/14.jpg"
                            data-toggle="tooltip"
                            title="Expandir foto"
                          >
                            <i class="qtyler-external"></i>
                            <span class="sr-only">Expandir foto</span>
                          </a>
                          <a
                            class="p-view prettyPhoto sr-only"
                            title=""
                            data-gal="prettyPhoto[product14-gal]"
                            href="~/assets/images/shop/14-1.jpg"
                          ></a>
                        </div>
                      </div>
                      <div class="corner-label sale">sale</div>
                    </div>
                    <div class="item-content">
                      <h3 class="entry-title">
                        <a href="shop-product"
                          >Heather grey long sleeve t-shirt</a
                        >
                      </h3>
                      <div class="price">
                        <span class="amount">$25.95</span>
                      </div>
                    </div>
                  </article>
                </li>
                <li class="product type-product">
                  <article class="vertical-item text-center women">
                    <div class="item-media-wrap bottommargin_25">
                      <div class="item-media">
                        <a href="shop-product">
                          <img src="~/assets/images/shop/15.jpg" alt="" />
                          <img src="~/assets/images/shop/15-1.jpg" alt="" />
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
                            data-gal="prettyPhoto[product15-gal]"
                            href="~/assets/images/shop/15.jpg"
                            data-toggle="tooltip"
                            title="Expandir foto"
                          >
                            <i class="qtyler-external"></i>
                            <span class="sr-only">Expandir foto</span>
                          </a>
                          <a
                            class="p-view prettyPhoto sr-only"
                            title=""
                            data-gal="prettyPhoto[product15-gal]"
                            href="~/assets/images/shop/15-1.jpg"
                          ></a>
                        </div>
                      </div>
                    </div>
                    <div class="item-content">
                      <h3 class="entry-title">
                        <a href="shop-product">White t-shirt</a>
                      </h3>
                      <div class="price">
                        <span class="amount">$14.95</span>
                      </div>
                    </div>
                  </article>
                </li>
              </ul>
            </div>
            <!-- eof .columns-* -->
            <div class="text-center topmargin_30">
              <ul class="pagination">
                <li class="disabled">
                  <a href="/"
                    ><span class="sr-only">Prev</span
                    ><i class="fa fa-angle-left" aria-hidden="true"></i
                  ></a>
                </li>
                <li class="active"><a href="/">1</a></li>
                <li><a href="/">2</a></li>
                <li><a href="/">3</a></li>
                <li><a href="/">4</a></li>
                <li>
                  <a href="/"
                    ><span class="sr-only">Next</span
                    ><i class="fa fa-angle-right" aria-hidden="true"></i
                  ></a>
                </li>
              </ul>
            </div>
          </div>
          <aside
            class="col-xs-12 col-sm-6 col-md-3 col-lg-3 col-md-pull-9 col-lg-pull-9 col-sm-offset-3 col-md-offset-0"
          >
            <div class="widget widget_categories">
              <h3 class="widget-title">Categories</h3>
              <ul class="greylinks">
                <li>
                  <a href="shop">Picanha turducken</a> <span>34</span>
                  <ul>
                    <li><a href="shop">Tail Meatball</a> <span>15</span></li>
                    <li><a href="shop">Sausage Beef</a> <span>19</span></li>
                  </ul>
                </li>
                <li>
                  <a href="shop">Jowl Corned</a> <span>27</span>
                  <ul>
                    <li><a href="shop">Pork Chop</a> <span>15</span></li>
                    <li><a href="shop">Beef Pork Loin</a> <span>12</span></li>
                  </ul>
                </li>
                <li><a href="#0">Ground Round</a> <span>38</span></li>
              </ul>
            </div>
            <div class="widget widget_search">
              <h3 class="widget-title black">Search Product</h3>
              <form method="get" class="searchform" action="./">
                <div class="form-group margin_0">
                  <label class="sr-only" for="widget-search">Search for:</label>
                  <input
                    id="widget-search"
                    type="text"
                    value=""
                    name="search"
                    class="form-control"
                    placeholder="keyword"
                  />
                  <button type="submit" class="theme_button">Search</button>
                </div>
              </form>
            </div>
            <div class="widget widget_shopping_cart">
              <h3 class="widget-title">Shopping Cart</h3>
              <div class="widget_shopping_cart_content">
                <ul class="cart_list product_list_widget">
                  <li class="media">
                    <div class="media-left media-middle">
                      <a href="shop-product">
                        <img src="~/assets/images/shop/03.jpg" alt="" />
                      </a>
                    </div>
                    <div class="media-body media-middle">
                      <a href="/" class="remove" title="Remove this item"></a>
                      <p class="darklinks">
                        <a href="shop-product">Heather grey pullover</a>
                      </p>
                      <span class="product-quantity">
                        <span class="price">$29.95</span> <span>x 1</span>
                      </span>
                    </div>
                  </li>
                  <li class="media">
                    <div class="media-left media-middle">
                      <a href="shop-product">
                        <img src="~/assets/images/shop/05.jpg" alt="" />
                      </a>
                    </div>
                    <div class="media-body media-middle">
                      <a href="/" class="remove" title="Remove this item"></a>
                      <p class="darklinks">
                        <a href="shop-product">Slim short dress</a>
                      </p>
                      <span class="product-quantity">
                        <span class="price">$34.95</span> <span>x 2</span>
                      </span>
                    </div>
                  </li>
                </ul>
                <p class="total grey">
                  <span>Subtotal:</span> <span class="price">$69.94</span>
                </p>
                <p class="buttons">
                  <a href="shop-cart" class="theme_button">View cart</a>
                  <a href="shop-cart" class="theme_button color1">Checkout</a>
                </p>
              </div>
            </div>
            <div class="widget widget_top_rated_products">
              <h3 class="widget-title">Top Products</h3>
              <ul class="media-list product_list_widget media_items_list">
                <li class="media">
                  <a class="media-left media-middle" href="shop-product">
                    <img
                      class="media-object muted_background"
                      src="~/assets/images/shop/04.jpg"
                      alt=""
                    />
                  </a>
                  <div class="media-body media-middle">
                    <p class="darklinks">
                      <a href="shop-product">Trainwreck</a>
                    </p>
                    <div
                      class="star-rating small-stars"
                      title="Rated 4.00 out of 5"
                    >
                      <span style="width: 90%">
                        <strong class="rating">4.00</strong> out of 5
                      </span>
                    </div>
                    <div class="price"><span class="amount">$49.00</span></div>
                  </div>
                </li>
                <li class="media">
                  <a class="media-left media-middle" href="shop-product">
                    <img
                      class="media-object muted_background"
                      src="~/assets/images/shop/05.jpg"
                      alt=""
                    />
                  </a>
                  <div class="media-body media-middle">
                    <p class="darklinks"><a href="shop-product">AK-47</a></p>
                    <div
                      class="star-rating small-stars"
                      title="Rated 3.00 out of 5"
                    >
                      <span style="width: 60%">
                        <strong class="rating">3.00</strong> out of 5
                      </span>
                    </div>
                    <div class="price">
                      <del>
                        <span class="amount">$125.00</span>
                      </del>
                      <ins>
                        <span class="amount">$99.00</span>
                      </ins>
                    </div>
                  </div>
                </li>
                <li class="media">
                  <a class="media-left media-middle" href="shop-product">
                    <img
                      class="media-object muted_background"
                      src="~/assets/images/shop/06.jpg"
                      alt=""
                    />
                  </a>
                  <div class="media-body media-middle">
                    <p class="darklinks">
                      <a href="shop-product">White Window</a>
                    </p>
                    <div
                      class="star-rating small-stars"
                      title="Rated 2.00 out of 5"
                    >
                      <span style="width: 40%">
                        <strong class="rating">2.00</strong> out of 5
                      </span>
                    </div>
                    <div class="price">
                      <del>
                        <span class="amount">$46.00</span>
                      </del>
                      <ins>
                        <span class="amount">$33.00</span>
                      </ins>
                    </div>
                  </div>
                </li>
              </ul>
            </div>
            <div class="widget widget_price_filter">
              <h3 class="widget-title">Price Filter</h3>
              <!-- price slider -->
              <form method="get" action="/" class="form-inline">
                <div class="slider-range-price"></div>
                <div class="price_label">
                  Price: <span class="price_from">2</span> -
                  <span class="price_to">35</span>
                </div>
                <div class="topmargin_10">
                  <button
                    type="submit"
                    class="theme_button color1 min_width_button"
                  >
                    Filter
                  </button>
                </div>
              </form>
            </div>
            <div class="widget widget_tag_cloud widget_product_tag_cloud">
              <h3 class="widget-title">Tags</h3>
              <div class="tagcloud">
                <a href="/" title="">XS</a> <a href="/" title="">S</a>
                <a href="/" title="">M</a> <a href="/" title="">L</a>
                <a href="/" title="">XL</a> <a href="/" title="">XXL</a>
              </div>
            </div>
          </aside>
          <!-- eof aside sidebar -->
        </div>
      </div>
    </section>
    <gallery-scroll />
  </main>
</template>
<script>
import BreadcrumbItem from '../components/breadcrumbItem.vue'
import GalleryScroll from '@/components/galleryScroll.vue'
export default {
  components: {
    GalleryScroll,
    BreadcrumbItem,
  },
}
</script>
