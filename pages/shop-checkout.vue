<template>
  <main>
    <breadcrumb-item title="Shop" uri="Checkout" />
    <section
      class="ls section_padding_top_150 section_padding_bottom_150 columns_padding_30"
    >
      <div class="container">
        <div class="row">
          <div class="col-xs-12 col-md-8 col-lg-8">
            <div class="shop-info">
              Returning customer?
              <a
                data-toggle="collapse"
                href="#registeredForm"
                aria-expanded="false"
                aria-controls="registeredForm"
                >Click here to login</a
              >
            </div>
            <div id="registeredForm" class="collapse">
              <form
                class="checkout with_padding big-padding with_background form-horizontal"
                role="form"
              >
                <p>
                  If you have shopped with us before, please enter your details
                  in the boxes below. If you are a new customer please proceed
                  to the Billing &amp; Shipping section.
                </p>
                <div class="form-group">
                  <label for="username" class="col-sm-3 control-label">
                    <span class="grey">Nick or email:</span>
                    <span class="required">*</span>
                  </label>
                  <div class="col-sm-9">
                    <input
                      id="username"
                      type="text"
                      class="form-control"
                      name="username"
                    />
                  </div>
                </div>
                <div class="form-group">
                  <label for="password" class="col-sm-3 control-label">
                    <span class="grey">Password:</span>
                    <span class="required">*</span>
                  </label>
                  <div class="col-sm-9">
                    <input
                      id="password"
                      class="form-control"
                      type="password"
                      name="password"
                    />
                  </div>
                </div>
                <div class="form-group">
                  <div class="col-sm-offset-3 col-sm-9">
                    <div class="checkbox">
                      <label for="rememberme" class="control-label">
                        <input
                          id="rememberme"
                          name="rememberme"
                          type="checkbox"
                          value="forever"
                        />
                        Remember me
                      </label>
                    </div>
                    <input
                      type="submit"
                      class="theme_button color1 min_width_button topmargin_20"
                      name="login"
                      value="Login"
                    />
                    <div class="lost_password">
                      <a href="/">Lost your password?</a>
                    </div>
                  </div>
                </div>
              </form>
            </div>
            <h2 class="topmargin_20 text-uppercase">Billing Address</h2>
            <form class="form-horizontal checkout shop-checkout" role="form">
              <div class="form-group">
                <label for="billing_country" class="col-sm-3 control-label">
                  <span class="grey">Country:</span>
                  <span class="required">*</span>
                </label>
                <div class="col-sm-9">
                  <select id="billing_country" name="billing_country">
                    <option value="">Select a country…</option>
                    <option value="AX">Åland Islands</option>
                    <option value="AF">Afghanistan</option>
                    <option value="AL">Albania</option>
                    <option value="GA">Gabon</option>
                    <option value="GM">Gambia</option>
                    <option value="GE">Georgia</option>
                    <option value="DE">Germany</option>
                    <option value="GH">Ghana</option>
                    <option value="AE">United Arab Emirates</option>
                    <option value="GB" selected="true">
                      United Kingdom (UK)
                    </option>
                    <option value="ZW">Zimbabwe</option>
                  </select>
                </div>
              </div>
              <div
                id="billing_first_name_field"
                class="form-group validate-required"
              >
                <label for="billing_first_name" class="col-sm-3 control-label">
                  <span class="grey">First Name:</span>
                  <span class="required">*</span>
                </label>
                <div class="col-sm-9">
                  <input
                    id="billing_first_name"
                    type="text"
                    class="form-control"
                    name="billing_first_name"
                    placeholder=""
                    value=""
                  />
                </div>
              </div>
              <div
                id="billing_last_name_field"
                class="form-group validate-required"
              >
                <label for="billing_last_name" class="col-sm-3 control-label">
                  <span class="grey">Last Name:</span>
                  <span class="required">*</span>
                </label>
                <div class="col-sm-9">
                  <input
                    id="billing_last_name"
                    type="text"
                    class="form-control"
                    name="billing_last_name"
                    placeholder=""
                    value=""
                  />
                </div>
              </div>
              <div id="billing_company_field" class="form-group">
                <label for="billing_company" class="col-sm-3 control-label">
                  <span class="grey">Company Name:</span>
                </label>
                <div class="col-sm-9">
                  <input
                    id="billing_company"
                    type="text"
                    class="form-control"
                    name="billing_company"
                    placeholder=""
                    value=""
                  />
                </div>
              </div>
              <div
                id="billing_address_fields"
                class="form-group address-field validate-required"
              >
                <label for="billing_address_1" class="col-sm-3 control-label">
                  <span class="grey">Address:</span>
                  <span class="required">*</span>
                </label>
                <div class="col-sm-9">
                  <input
                    id="billing_address_1"
                    type="text"
                    class="form-control"
                    name="billing_address_1"
                    placeholder=""
                    value=""
                  />
                </div>
              </div>
              <div class="form-group">
                <div class="col-sm-offset-3 col-sm-9">
                  <input
                    id="billing_address_2"
                    type="text"
                    class="form-control"
                    name="billing_address_2"
                    placeholder=""
                    value=""
                  />
                </div>
              </div>
              <div
                id="billing_city_field"
                class="form-group address-field validate-required"
              >
                <label for="billing_city" class="col-sm-3 control-label">
                  <span class="grey">Town / City:</span>
                  <span class="required">*</span>
                </label>
                <div class="col-sm-9">
                  <input
                    id="billing_city"
                    type="text"
                    class="form-control"
                    name="billing_city"
                    placeholder=""
                    value=""
                  />
                </div>
              </div>
              <div
                id="billing_state_field"
                class="form-group address-field validate-state"
              >
                <label for="billing_state" class="col-sm-3 control-label">
                  <span class="grey">County:</span>
                </label>
                <div class="col-sm-9">
                  <input
                    id="billing_state"
                    type="text"
                    class="form-control"
                    value=""
                    placeholder=""
                    name="billing_state"
                  />
                </div>
              </div>
              <div
                id="billing_postcode_field"
                class="form-group address-field validate-required validate-postcode"
              >
                <label for="billing_postcode" class="col-sm-3 control-label">
                  <span class="grey">Postcode:</span>
                  <span class="required">*</span>
                </label>
                <div class="col-sm-9">
                  <input
                    id="billing_postcode"
                    type="text"
                    class="form-control"
                    name="billing_postcode"
                    placeholder=""
                    value=""
                  />
                </div>
              </div>
              <div
                id="billing_email_field"
                class="form-group validate-required validate-email"
              >
                <label for="billing_email" class="col-sm-3 control-label">
                  <span class="grey">Email Address:</span>
                  <span class="required">*</span>
                </label>
                <div class="col-sm-9">
                  <input
                    id="billing_email"
                    type="text"
                    class="form-control"
                    name="billing_email"
                    placeholder=""
                    value=""
                  />
                </div>
              </div>
              <div
                id="billing_phone_field"
                class="form-group validate-required validate-phone"
              >
                <label for="billing_phone" class="col-sm-3 control-label">
                  <span class="grey">Phone:</span>
                  <span class="required">*</span>
                </label>
                <div class="col-sm-9">
                  <input
                    id="billing_phone"
                    type="text"
                    class="form-control"
                    name="billing_phone"
                    placeholder=""
                    value=""
                  />
                </div>
              </div>
              <div class="form-group">
                <div class="col-sm-offset-3 col-sm-9">
                  <div class="checkbox">
                    <label>
                      <input type="checkbox" /> Create an Account?
                    </label>
                  </div>
                  <div class="checkbox">
                    <label>
                      <input type="checkbox" /> Shop to Billing Address?
                    </label>
                  </div>
                </div>
              </div>
              <div class="form-group">
                <label for="order_comments" class="col-sm-3 control-label">
                  <span class="grey">Order Notes:</span>
                </label>
                <div class="col-sm-9">
                  <textarea
                    id="order_comments"
                    name="order_comments"
                    class="form-control"
                    placeholder=""
                    rows="3"
                  ></textarea>
                </div>
              </div>
            </form>
          </div>
          <!--eof .col-sm-8 (main content)-->
          <!-- sidebar -->
          <aside
            class="col-xs-12 col-sm-6 col-sm-offset-3 col-md-4 col-md-offset-0 col-lg-4"
          >
            <h3 id="order_review_heading" class="widget-title">Your order</h3>
            <div id="order_review" class="shop-checkout-review-order">
              <table class="table shop_table shop-checkout-review-order-table">
                <thead>
                  <tr>
                    <td class="product-name">Product</td>
                    <td class="product-total">Total</td>
                  </tr>
                </thead>
                <tbody>
                  <tr class="cart_item">
                    <td class="product-name">
                      Lipsum Sit <span class="product-quantity">× 1</span>
                    </td>
                    <td class="product-total">
                      <span class="amount grey">$20.00</span>
                    </td>
                  </tr>
                </tbody>
                <tfoot>
                  <tr class="cart-subtotal">
                    <td>Subtotal:</td>
                    <td><span class="amount grey">$20.00</span></td>
                  </tr>
                  <tr class="shipping">
                    <td>Shipping:</td>
                    <td><span class="grey">Free Shipping</span></td>
                  </tr>
                  <tr class="order-total">
                    <td>Total:</td>
                    <td>
                      <span class="amount grey">
                        <strong>$20.00</strong>
                      </span>
                    </td>
                  </tr>
                </tfoot>
              </table>
              <div id="payment" class="shop-checkout-payment">
                <h3 class="widget-title">Payment</h3>
                <ul class="list1 no-bullets payment_methods methods">
                  <li class="payment_method_bacs">
                    <div class="radio">
                      <label for="payment_method_bacs">
                        <input
                          id="payment_method_bacs"
                          type="radio"
                          name="payment_method"
                          value="bacs"
                          checked
                        />
                        <span class="grey">Direct Bank Transfer</span>
                      </label>
                    </div>
                    <div class="payment_box payment_method_bacs">
                      <p>
                        Make your payment directly into our bank account. Please
                        use your Order ID as the payment reference. Your order
                        won’t be shipped until the funds have cleared in our
                        account.
                      </p>
                    </div>
                  </li>
                  <li class="payment_method_cheque">
                    <div class="radio">
                      <label for="payment_method_cheque">
                        <input
                          id="payment_method_cheque"
                          type="radio"
                          name="payment_method"
                          value="cheque"
                        />
                        <span class="grey">Cheque Payment</span>
                      </label>
                    </div>
                  </li>
                  <li class="payment_method_paypal">
                    <div class="radio">
                      <label for="payment_method_paypal">
                        <input
                          id="payment_method_paypal"
                          type="radio"
                          name="payment_method"
                          value="paypal"
                        />
                        <span class="grey">PayPal</span>
                      </label>
                    </div>
                  </li>
                </ul>
                <div class="place-order topmargin_30">
                  <button
                    id="place_order"
                    type="submit"
                    class="theme_button color1 min_width_button"
                    name="checkout_place_order"
                  >
                    Place order
                  </button>
                </div>
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
