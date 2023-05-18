<template>
  <main>
    <breadcrumb-item title="Shop" uri="Register" />
    <section class="ls section_padding_top_150 section_padding_bottom_150">
      <div class="container">
        <div class="row">
          <form class="shop-register" role="form">
            <div class="col-sm-6">
              <div
                id="billing_first_name_field"
                class="form-group validate-required"
              >
                <label for="billing_first_name" class="control-label">
                  <span class="grey">First Name:</span>
                  <span class="required">*</span>
                </label>
                <input
                  id="billing_first_name"
                  type="text"
                  class="form-control"
                  name="billing_first_name"
                  placeholder=""
                  value=""
                />
              </div>
              <div id="billing_company_field" class="form-group">
                <label for="billing_company" class="control-label">
                  <span class="grey">Company Name:</span>
                </label>
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
            <div class="col-sm-6">
              <div
                id="billing_last_name_field"
                class="form-group validate-required"
              >
                <label for="billing_last_name" class="control-label">
                  <span class="grey">Last Name:</span>
                  <span class="required">*</span>
                </label>
                <input
                  id="billing_last_name"
                  type="text"
                  class="form-control"
                  name="billing_last_name"
                  placeholder=""
                  value=""
                />
              </div>
              <div
                id="billing_email_field"
                class="form-group validate-required validate-email"
              >
                <label for="billing_email" class="control-label">
                  <span class="grey">Email Address:</span>
                  <span class="required">*</span>
                </label>
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
            <div class="col-sm-12">
              <div
                id="billing_address_fields"
                class="form-group address-field validate-required"
              >
                <label for="billing_address_1" class="control-label">
                  <span class="grey">Address:</span>
                  <span class="required">*</span>
                </label>
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
            <div class="col-sm-6">
              <div
                id="billing_city_field"
                class="form-group address-field validate-required"
              >
                <label for="billing_city" class="control-label">
                  <span class="grey">Town / City:</span>
                  <span class="required">*</span>
                </label>
                <input
                  id="billing_city"
                  type="text"
                  class="form-control"
                  name="billing_city"
                  placeholder=""
                  value=""
                />
              </div>
              <div
                id="billing_postcode_field"
                class="form-group address-field validate-required validate-postcode"
              >
                <label for="billing_postcode" class="control-label">
                  <span class="grey">Postcode:</span>
                  <span class="required">*</span>
                </label>
                <input
                  id="billing_postcode"
                  type="text"
                  class="form-control"
                  name="billing_postcode"
                  placeholder=""
                  value=""
                />
              </div>
              <div
                id="billing_phone_field"
                class="form-group validate-required validate-phone"
              >
                <label for="billing_phone" class="control-label">
                  <span class="grey">Phone:</span>
                  <span class="required">*</span>
                </label>
                <input
                  id="billing_phone"
                  type="text"
                  class="form-control"
                  name="billing_phone"
                  placeholder=""
                  value=""
                />
              </div>
              <div id="billing_password_field" class="form-group">
                <label for="billing_password" class="control-label">
                  <span class="grey">Password:</span>
                  <span class="required">*</span>
                </label>
                <input
                  id="billing_password"
                  type="text"
                  class="form-control"
                  name="billing_password"
                  placeholder=""
                  value=""
                />
              </div>
              <div class="form-group">
                <div class="radio">
                  <label>
                    <input type="radio" name="optionsRadios" /> Ship to this
                    address
                  </label>
                </div>
                <div class="radio">
                  <label>
                    <input type="radio" name="optionsRadios" /> Ship to
                    different address
                  </label>
                </div>
              </div>
            </div>
            <div class="col-sm-6">
              <div class="form-group">
                <label for="billing_state" class="control-label">
                  <span class="grey">State/Province:</span>
                  <span class="required">*</span>
                </label>
                <select id="billing_state" name="billing_state">
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
              <div class="form-group">
                <label for="billing_country" class="control-label">
                  <span class="grey">Country:</span>
                  <span class="required">*</span>
                </label>
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
              <div
                id="billing_fax_field"
                class="form-group validate-required validate-fax"
              >
                <label for="billing_fax" class="control-label">
                  <span class="grey">Fax:</span>
                  <span class="required">*</span>
                </label>
                <input
                  id="billing_fax"
                  type="text"
                  class="form-control"
                  name="billing_fax"
                  placeholder=""
                  value=""
                />
              </div>
              <div id="billing_password2_field" class="form-group">
                <label for="billing_password2" class="control-label">
                  <span class="grey">Confirm Password:</span>
                  <span class="required">*</span>
                </label>
                <input
                  id="billing_password2"
                  type="text"
                  class="form-control"
                  name="billing_password2"
                  placeholder=""
                  value=""
                />
              </div>
            </div>
            <div class="col-sm-12">
              <button type="submit" class="theme_button color1 topmargin_30">
                Register Now
              </button>
              <button type="reset" class="theme_button">Clear Form</button>
            </div>
          </form>
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
