<template>
  <main>
    <breadcrumb-item title="Shop" uri="Cart" />
    <section
      class="ls section_padding_top_150 section_padding_bottom_150 columns_padding_30"
    >
      <div class="container">
        <div class="row">
          <!-- <div class="col-xs-12 col-md-8 col-lg-8 col-md-push-4 col-lg-push-4"> -->
          <div class="col-sm-12">
            <div class="table-responsive">
              <table class="table shop_table cart cart-table">
                <thead>
                  <tr>
                    <td class="product-info">Product</td>
                    <td class="product-price-td">Price</td>
                    <td class="product-quantity">Quantity</td>
                    <td class="product-subtotal">Subtotal</td>
                    <td class="product-remove">&nbsp;</td>
                  </tr>
                </thead>
                <tbody>
                  <tr class="cart_item">
                    <td class="product-info">
                      <div class="media">
                        <div class="media-left">
                          <a href="shop-product">
                            <img
                              class="media-object cart-product-image"
                              src="~/assets/images/shop/01.jpg"
                              alt=""
                            />
                          </a>
                        </div>
                        <div class="media-body">
                          <h4 class="media-heading">
                            <a href="shop-product">At vero eos et accusam</a>
                          </h4>
                          <span class="grey">Color:</span> Black<br />
                          <span class="grey">Size:</span> M
                        </div>
                      </div>
                    </td>
                    <td class="product-price">
                      <span class="currencies">$</span
                      ><span class="amount">199.00</span>
                    </td>
                    <td class="product-quantity">
                      <div class="quantity">
                        <input type="button" value="-" class="minus" />
                        <i class="fa fa-angle-down" aria-hidden="true"></i>
                        <input
                          type="number"
                          step="1"
                          min="0"
                          name="product_quantity"
                          value="1"
                          title="Qty"
                          class="form-control"
                        />
                        <input type="button" value="+" class="plus" />
                        <i class="fa fa-angle-up" aria-hidden="true"></i>
                      </div>
                    </td>
                    <td class="product-subtotal">
                      <span class="currencies">$</span
                      ><span class="amount">199.00</span>
                    </td>
                    <td class="product-remove">
                      <a
                        href="#"
                        class="remove fontsize_20"
                        title="Remove this item"
                      >
                        <i class="fa fa-trash-o"></i>
                      </a>
                    </td>
                  </tr>
                  <tr class="cart_item">
                    <td class="product-info">
                      <div class="media">
                        <div class="media-left">
                          <a href="shop-product">
                            <img
                              class="media-object cart-product-image"
                              src="~/assets/images/shop/02.jpg"
                              alt=""
                            />
                          </a>
                        </div>
                        <div class="media-body">
                          <h4 class="media-heading">
                            <a href="shop-product"
                              >Justo duo dolores et ea rebum</a
                            >
                          </h4>
                          <span class="grey">Size:</span> XL
                        </div>
                      </div>
                    </td>
                    <td class="product-price">
                      <span class="currencies">$</span
                      ><span class="amount">100.00</span>
                    </td>
                    <td class="product-quantity">
                      <div class="quantity">
                        <input type="button" value="-" class="minus" />
                        <i class="fa fa-angle-down" aria-hidden="true"></i>
                        <input
                          type="number"
                          step="1"
                          min="0"
                          name="product_quantity"
                          value="1"
                          title="Qty"
                          class="form-control"
                        />
                        <input type="button" value="+" class="plus" />
                        <i class="fa fa-angle-up" aria-hidden="true"></i>
                      </div>
                    </td>
                    <td class="product-subtotal">
                      <span class="currencies">$</span
                      ><span class="amount">100.00</span>
                    </td>
                    <td class="product-remove">
                      <a
                        href="#"
                        class="remove fontsize_20"
                        title="Remove this item"
                      >
                        <i class="fa fa-trash-o"></i>
                      </a>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
            <div class="cart-buttons">
              <a class="theme_button color1" href="#">Countinue Shopping</a>
              <button
                type="submit"
                class="theme_button inverse"
                name="update_cart"
              >
                Update Cart
              </button>
              <button type="submit" class="theme_button">
                Proceed to Checkout
              </button>
            </div>
            <div class="cart-collaterals topmargin_50">
              <div class="cart_totals">
                <h3>Cart Totals</h3>
                <table class="table">
                  <tbody>
                    <tr class="cart-subtotal">
                      <td>Cart Subtotal</td>
                      <td>
                        <span class="currencies">$</span
                        ><span class="amount">299.00</span>
                      </td>
                    </tr>
                    <tr class="shipping">
                      <td>Shipping and Handling</td>
                      <td>Free Shipping</td>
                    </tr>
                    <tr class="order-total">
                      <td class="grey">Order Total</td>
                      <td>
                        <strong class="grey"
                          ><span class="currencies">$</span
                          ><span class="amount">299.00</span>
                        </strong>
                      </td>
                    </tr>
                  </tbody>
                </table>
              </div>
            </div>
            <div class="row">
              <div class="col-md-6">
                <div class="coupon with_padding big-padding with_background">
                  <h3>Discount Codes</h3>
                  <p>Enter coupon code if you have one</p>
                  <div class="form-group">
                    <label class="sr-only" for="coupon_code">Coupon:</label>
                    <input
                      id="coupon_code"
                      type="text"
                      name="coupon_code"
                      class="form-control"
                      value=""
                      placeholder="Coupon code"
                    />
                  </div>
                  <div class="topmargin_30">
                    <a class="theme_button" href="#">Apply Coupon</a>
                  </div>
                </div>
              </div>
              <div class="col-md-6">
                <div
                  class="shipping-calculator-form with_padding big-padding with_background"
                >
                  <h3>Shipping &amp; Tax</h3>
                  <p>Enter destination to get shipping</p>
                  <div class="form-group">
                    <select
                      id="calc_shipping_country"
                      name="calc_shipping_country"
                      class="country_to_state"
                    >
                      <option value="">Select a country…</option>
                      <option value="AX">Åland Islands</option>
                      <option value="OM">Oman</option>
                      <option value="GB" selected="true">
                        United Kingdom (UK)
                      </option>
                    </select>
                  </div>
                  <div class="form-group">
                    <input
                      id="calc_shipping_state"
                      type="text"
                      class="form-control"
                      value=""
                      placeholder="State / county"
                      name="calc_shipping_state"
                    />
                  </div>
                  <div class="form-group">
                    <input
                      id="calc_shipping_postcode"
                      type="text"
                      class="form-control"
                      value=""
                      placeholder="Postcode / Zip"
                      name="calc_shipping_postcode"
                    />
                  </div>
                  <div class="topmargin_30">
                    <button
                      type="submit"
                      name="calc_shipping"
                      class="theme_button"
                      value="1"
                    >
                      Update Totals
                    </button>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!--eof .col-sm-8 (main content)-->
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
