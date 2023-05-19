<template>
  <section id="gallery" class="ls fluid_padding_0 columns_padding_0">
    <div class="container-fluid">
      <div class="row">
        <div class="col-xs-12">
          <div
            class="owl-carousel gallery-carousel framed"
            data-responsive-xlg="6"
            data-responsive-lg="5"
            data-responsive-md="4"
            data-responsive-sm="3"
            data-responsive-xs="3"
            data-responsive-xxs="2"
            data-loop="true"
            data-margin="0"
            data-nav="true"
          >
            <div v-for="image in images" :key="image" class="vertical-item">
              <div class="item-media">
                <img :src="`/_nuxt/${image}`" alt="" />
                <a
                  class="abs-link prettyPhoto"
                  data-gal="prettyPhoto[gal]"
                  title=""
                  :href="`/_nuxt/${image}`"
                >
                </a>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>
<script>
const images = [
  'assets/images/gallery/01.jpg',
  'assets/images/gallery/02.jpg',
  'assets/images/gallery/03.jpg',
  'assets/images/gallery/04.jpg',
  'assets/images/gallery/05.jpg',
  'assets/images/gallery/06.jpg',
  'assets/images/gallery/07.jpg',
  'assets/images/gallery/08.jpg',
  'assets/images/gallery/09.jpg',
  'assets/images/gallery/10.jpg',
  'assets/images/gallery/11.jpg',
  'assets/images/gallery/12.jpg',
]
export default {
  data: function () {
    return { images }
  },
}
</script>
