<template>
  <main>
    <section class="page_breadcrumbs ls background_cover section_padding_50">
      <div class="container">
        <div class="row">
          <div class="col-xs-12 text-center">
            <h1 class="sr-only">Single Product</h1>
            <ol class="breadcrumb darklinks">
              <li><a href="./"> Home </a></li>
              <li><a href="/">Shop</a></li>
              <li class="active"><span>Single Product</span></li>
            </ol>
          </div>
        </div>
      </div>
    </section>
    <section
      class="ls section_padding_top_150 section_padding_bottom_150 columns_padding_30"
    >
      <div class="container">
        <div class="row">
          <div class="col-xs-12 col-md-9 col-lg-9 col-md-push-3 col-lg-push-3">
            <div
              itemtype="http://schema.org/Product"
              class="product type-product row columns_padding_30 columns_margin_bottom_30"
            >
              <div class="col-sm-6">
                <div class="with-corner-label">
                  <div class="images text-center">
                    <a
                      href="~/assets/images/shop/01.jpg"
                      itemprop="image"
                      class="woocommerce-main-image zoom prettyPhoto"
                      data-gal="prettyPhoto[product-gallery]"
                    >
                      <img
                        src="~/assets/images/shop/01.jpg"
                        class="attachment-shop_single wp-post-image"
                        alt=""
                        title=""
                      />
                    </a>
                    <div class="corner-label hot">Quente</div>
                  </div>
                  <!--eof .images -->
                </div>
                <div class="thumbnails-wrap">
                  <div
                    id="product-thumbnails"
                    class="owl-carousel thumbnails product-thumbnails"
                    data-margin="10"
                    data-nav="false"
                    data-dots="true"
                    data-responsive-lg="4"
                    data-responsive-md="4"
                    data-responsive-sm="3"
                    data-responsive-xs="2"
                    data-responsive-xxs="2"
                  >
                    <a
                      href="~/assets/images/shop/01.jpg"
                      class="zoom first"
                      title=""
                      data-gal="prettyPhoto[product-gallery]"
                    >
                      <img
                        src="~/assets/images/shop/01.jpg"
                        class="attachment-shop_thumbnail"
                        alt=""
                      />
                    </a>
                    <a
                      href="~/assets/images/shop/01-1.jpg"
                      class="zoom first"
                      title=""
                      data-gal="prettyPhoto[product-gallery]"
                    >
                      <img
                        src="~/assets/images/shop/01-1.jpg"
                        class="attachment-shop_thumbnail"
                        alt=""
                      />
                    </a>
                  </div>
                </div>
                <!-- eof .images -->
              </div>
              <div class="summary entry-summary col-sm-6">
                <h1 itemprop="name" class="product_title">Black Tank Top</h1>
                <div class="product-rating">
                  <span class="review-links pull-right greylinks">
                    <a href="#reviews" class="review-link">
                      (<span class="count">5</span> customer review)
                    </a>
                  </span>
                  <div class="star-rating">
                    <span style="width: 80%">
                      Rated <strong class="rating">4.00</strong> out of 5 based
                      on <span class="rating">5</span> customer rating
                    </span>
                  </div>
                </div>
                <span class="price">
                  <span class="amount">$15.00 - $400.00</span>
                </span>
                <div class="short-description">
                  <p>
                    Facete scriptorem cu sed. Vel aliquam sanctus ei. His ne
                    maluisset urbanitas definitionem, viris alienum blandit an
                    mea ut probo.
                  </p>
                </div>
                <form class="cart" method="post" enctype="multipart/form-data">
                  <table class="variations">
                    <tbody>
                      <tr>
                        <td class=""><label for="pa_color">Color:</label></td>
                        <td class="value">
                          <select
                            id="pa_color"
                            class=""
                            name="attribute_pa_weight"
                          >
                            <option value="">Choose Color</option>
                            <option value="red">red</option>
                            <option value="green">green</option>
                            <option value="blue">blue</option>
                            <option value="pink">pink</option>
                            <option value="yellow">yellow</option>
                          </select>
                        </td>
                      </tr>
                      <tr>
                        <td class=""><label for="pa_color">Size:</label></td>
                        <td class="value">
                          <select
                            id="pa_size"
                            class=""
                            name="attribute_pa_weight"
                          >
                            <option value="">Choose Size</option>
                            <option value="xs">XS</option>
                            <option value="s">S</option>
                            <option value="m">M</option>
                            <option value="l">L</option>
                            <option value="xl">XL</option>
                          </select>
                        </td>
                      </tr>
                    </tbody>
                  </table>
                  <div>
                    <span class="quantity form-group">
                      <input type="button" value="+" class="plus" />
                      <i class="fa fa-angle-up" aria-hidden="true"></i>
                      <input
                        id="product_quantity"
                        type="number"
                        step="1"
                        min="0"
                        name="product_quantity"
                        value="1"
                        title="Qty"
                        class="form-control"
                      />
                      <input type="button" value="-" class="minus" />
                      <i class="fa fa-angle-down" aria-hidden="true"></i>
                    </span>
                    <button
                      type="submit"
                      name="add-to-cart"
                      value=""
                      class="theme_button add_to_cart_button"
                    >
                      Adicionar ao carrinho
                    </button>
                  </div>
                </form>
                <div class="product_meta highlightlinks">
                  <ul class="list1 feature-list bottommargin_0">
                    <li><span class="grey">SKU:</span> n/a</li>
                    <li>
                      <span class="grey">Category:</span>
                      <a href="/">Drumstick</a>, <a href="/">Strip</a>
                    </li>
                    <li>
                      <span class="grey">Tag:</span> <a href="/">Engineering</a>
                    </li>
                  </ul>
                </div>
              </div>
              <!-- .summary.col- -->
            </div>
            <!-- .product.row -->
            <div class="woocommerce-tabs">
              <!-- Nav tabs -->
              <ul class="nav nav-tabs wc-tabs" role="tablist">
                <li class="active">
                  <a href="#details_tab" role="tab" data-toggle="tab"
                    >Description</a
                  >
                </li>
                <li>
                  <a href="#additional_tab" role="tab" data-toggle="tab"
                    >Additional</a
                  >
                </li>
                <li>
                  <a href="#reviews_tab" role="tab" data-toggle="tab"
                    >Reviews</a
                  >
                </li>
                <li>
                  <a href="#custom_tab" role="tab" data-toggle="tab">Custom</a>
                </li>
              </ul>
              <!-- Tab panes -->
              <div class="tab-content big-padding top-color-border">
                <div id="details_tab" class="tab-pane fade in active">
                  <p>
                    Duis autem veiudolorn hendrerit vulputate velit esse
                    molestie. consequat, vel illum dolore eu feugiat nulla
                    facilisis at vereros accumsan etiusto dignissim:
                  </p>
                  <ul class="list2 darklinks">
                    <li><a href="/">Lorem ipsum dolor sit amet</a></li>
                    <li><a href="/">Sint animi non ut sed</a></li>
                    <li><a href="/">Eaque blanditiis nemo</a></li>
                    <li><a href="/">Amet, consectetur adipisicing</a></li>
                    <li><a href="/">Blanditiis nemo quaerat</a></li>
                  </ul>
                  <div class="well">
                    <strong class="highlight">Warning!</strong> Lorem ipsum
                    dolor sit amet, consectetur adipisicing elit, sed do eiusmod
                    tempor incididunt ut labore et dolore magna aliqua. Ut enim
                    ad minim veniam
                  </div>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                    sed do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    Duis aute irure dolor in reprehenderit in voluptate velit
                    esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
                    occaecat cupidatat non proident, sunt in culpa qui officia
                    deserunt mollit anim id est laborum.
                  </p>
                </div>
                <div id="additional_tab" class="tab-pane fade">
                  <h2>Chemdawg Details</h2>
                  <table class="table margin_0">
                    <tr>
                      <th class="grey medium">Aromas:</th>
                      <td>
                        <span class="highlight4"
                          >Shoulder, Rump, Filet, Mignon, Kevin</span
                        >
                      </td>
                    </tr>
                    <tr>
                      <th class="grey medium">Flavors:</th>
                      <td>
                        <span class="highlight4"
                          >Drumstick, Chuck, Bresaola, Filet, Mignon</span
                        >
                      </td>
                    </tr>
                    <tr>
                      <th class="grey medium">Effects:</th>
                      <td>
                        <span class="highlight4"
                          >Meatloaf, Jerky, Kevin, Pancetta</span
                        >
                      </td>
                    </tr>
                    <tr>
                      <th class="grey medium">Symptoms:</th>
                      <td>
                        <span class="highlight4"
                          >Fatback, Chicken, Tongue, Porchetta, Ball</span
                        >
                      </td>
                    </tr>
                  </table>
                </div>
                <div id="reviews_tab" class="tab-pane fade">
                  <div id="comments" class="comments-area">
                    <ol class="commentlist">
                      <li id="li-comment-22" class="comment">
                        <div class="comment_container">
                          <img
                            alt=""
                            src="http://0.gravatar.com/avatar/?s=60&amp;d=mm&amp;r=g"
                            srcset="
                              http://1.gravatar.com/avatar/?s=120&amp;d=mm&amp;r=g 2x
                            "
                            class="avatar avatar-60 photo avatar-default"
                            height="60"
                            width="60"
                          />
                          <div class="comment-text">
                            <div class="meta darklinks">
                              <a
                                class="author_url"
                                rel="external nofollow"
                                href="#"
                                >Timothy Bawerman</a
                              >
                              <span class="comment-date grey">
                                <time datetime="2017-10-03T08:50:40+00:00">
                                  20 jan, 2018
                                </time>
                              </span>
                            </div>
                            <div class="star-rating">
                              <span style="width: 100%"
                                >Rated <strong class="rating">5</strong> out of
                                5</span
                              >
                            </div>
                            <div class="description">
                              <p>
                                Aliquam sodales, diam dictum rhoncus laoreet,
                                metus velit viverra tellus, non gravida est odio
                                in risus. Integer vehicula, justo quis efficitur
                                varius, diam elit tristique magna, eget pulvinar
                                turpis massa et velit.
                              </p>
                            </div>
                          </div>
                        </div>
                      </li>
                    </ol>
                    <!-- .comment-list -->
                  </div>
                  <!-- #comments -->
                  <div id="respond" class="comment-respond">
                    <h3>Write Your Own Review</h3>
                    <div>
                      <span class="grey">Your rating:</span>
                      <p class="stars">
                        <a class="star-1" href="#">1</a
                        ><a class="star-2" href="#">2</a
                        ><a class="star-3" href="#">3</a
                        ><a class="star-4" href="#">4</a
                        ><a class="star-5" href="#">5</a>
                      </p>
                    </div>
                    <form
                      id="commentform"
                      class="comment-form"
                      method="post"
                      action="./"
                    >
                      <div class="row columns_padding_10">
                        <div class="col-md-6">
                          <p class="comment-form-author">
                            <label for="author"
                              >Name <span class="required">*</span></label
                            >
                            <!-- <i class="rt-icon2-user-outline"></i> --><input
                              id="author"
                              type="text"
                              aria-required="true"
                              size="30"
                              value=""
                              name="author"
                              class="form-control"
                              placeholder="Your Name"
                            />
                          </p>
                        </div>
                        <div class="col-md-6">
                          <p class="comment-form-email">
                            <label for="comment_email"
                              >Email <span class="required">*</span></label
                            >
                            <!-- <i class="rt-icon2-mail2"></i> --><input
                              id="comment_email"
                              type="email"
                              aria-required="true"
                              size="30"
                              value=""
                              name="comment_email"
                              class="form-control"
                              placeholder="Email Address"
                            />
                          </p>
                        </div>
                        <div class="col-md-12">
                          <p class="comment-form-chat">
                            <label for="comment">Comment</label>
                            <!-- <i class="rt-icon2-pencil3"></i> --><textarea
                              id="comment"
                              aria-required="true"
                              rows="3"
                              cols="45"
                              name="comment"
                              class="form-control"
                              placeholder="Review"
                            ></textarea>
                          </p>
                        </div>
                      </div>
                      <p class="form-submit topmargin_30">
                        <button
                          id="submit"
                          type="submit"
                          name="submit"
                          class="theme_button gradient1"
                        >
                          Submit Review
                        </button>
                        <button id="reset" type="reset" class="theme_button">
                          Clear Form
                        </button>
                      </p>
                    </form>
                  </div>
                  <!-- #respond -->
                </div>
                <div id="custom_tab" class="tab-pane fade">
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipisicing elit,
                    sed do eiusmod tempor incididunt ut labore et dolore magna
                    aliqua. Ut enim ad minim veniam, quis nostrud exercitation
                    ullamco laboris nisi ut aliquip ex ea commodo consequat.
                    Duis aute irure dolor in reprehenderit in voluptate velit
                    esse cillum dolore eu fugiat nulla pariatur. Excepteur sint
                    occaecat cupidatat non proident, sunt in culpa qui officia
                    deserunt mollit anim id est laborum.
                  </p>
                </div>
              </div>
              <!-- eof .tab-content -->
            </div>
            <!-- .woocommerce-tabs -->
            <div class="related-products">
              <h2>Related Products</h2>
              <div
                class="owl-carousel with_shadow_items"
                data-dots="false"
                data-nav="true"
                data-loop="true"
                data-autoplay="true"
                data-responsive-lg="3"
                data-responsive-md="3"
                data-responsive-sm="3"
                data-responsive-xs="2"
              >
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
                      <a href="shop-product">White pullover</a>
                    </h3>
                    <div class="price"><span class="amount">$19.95</span></div>
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
                      <a href="shop-product">Heather grey pullover</a>
                    </h3>
                    <div class="price"><span class="amount">$29.95</span></div>
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
                      <a href="shop-product">White sport bra</a>
                    </h3>
                    <div class="price"><span class="amount">$14.95</span></div>
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
                      <a href="shop-product">Slim short dress</a>
                    </h3>
                    <div class="price"><span class="amount">$34.95</span></div>
                  </div>
                </article>
              </div>
            </div>
          </div>
          <!--eof .col-sm-8 (main content)-->
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
