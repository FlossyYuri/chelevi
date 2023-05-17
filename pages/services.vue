<template>
  <main>
    <section class="page_breadcrumbs ls background_cover section_padding_50">
      <div class="container">
        <div class="row">
          <div class="col-xs-12 text-center">
            <h1 class="sr-only">Services</h1>
            <ol class="breadcrumb darklinks">
              <li><a href="./"> Home </a></li>
              <li><a href="/">Pages</a></li>
              <li class="active"><span>Services</span></li>
            </ol>
          </div>
        </div>
      </div>
    </section>
    <section class="ls section_padding_top_150 section_padding_bottom_150">
      <div class="container">
        <div class="row">
          <div class="col-xs-12">
            <div
              class="isotope_container isotope row masonry-layout columns_margin_bottom_20"
            >
              <div class="isotope-item col-xs-12 col-sm-6">
                <article
                  class="vertical-item service-item content-padding big-padding with_shadow text-center"
                >
                  <div class="item-media-wrap">
                    <div class="item-media">
                      <img src="~/assets/images/services/01.jpg" alt="" />
                      <a href="service-single" class="abs-link"></a>
                    </div>
                  </div>
                  <div class="item-content">
                    <h3 class="entry-title">
                      <a href="service-single">Fashion Design</a>
                    </h3>
                    <div class="entry-content">
                      <p>
                        Audiam apeirian sit at, mea an tibique insolens
                        similique. Te qui veritus mnesarchum. Quot unum molestie
                        an vim, sea case graecis detraxit ad, viris primis ex
                        mei.
                      </p>
                    </div>
                  </div>
                </article>
              </div>
              <div class="isotope-item col-xs-12 col-sm-6">
                <article
                  class="vertical-item service-item content-padding big-padding with_shadow text-center"
                >
                  <div class="item-media-wrap">
                    <div class="item-media">
                      <img src="~/assets/images/services/02.jpg" alt="" />
                      <a href="service-single" class="abs-link"></a>
                    </div>
                  </div>
                  <div class="item-content">
                    <h3 class="entry-title">
                      <a href="service-single">Development</a>
                    </h3>
                    <div class="entry-content">
                      <p>
                        Vim iriure omittantur ullamcorper ea, eam eu natum
                        nemore oblique. Luptatum maiestatis no eum, sit id malis
                        postulant evertitur. Omittam iudicabit est ad.
                      </p>
                    </div>
                  </div>
                </article>
              </div>
              <div class="isotope-item col-xs-12 col-sm-6">
                <article
                  class="vertical-item service-item content-padding big-padding with_shadow text-center"
                >
                  <div class="item-media-wrap">
                    <div class="item-media">
                      <img src="~/assets/images/services/03.jpg" alt="" />
                      <a href="service-single" class="abs-link"></a>
                    </div>
                  </div>
                  <div class="item-content">
                    <h3 class="entry-title">
                      <a href="service-single">Apparel</a>
                    </h3>
                    <div class="entry-content">
                      <p>
                        Eos timeam copiosae ne, duo eu saepe maiorum. Singulis
                        adolescens an usu. Vis dicunt inciderint in, malorum
                        blandit quaerendum ne his homero.
                      </p>
                    </div>
                  </div>
                </article>
              </div>
              <div class="isotope-item col-xs-12 col-sm-6">
                <article
                  class="vertical-item service-item content-padding big-padding with_shadow text-center"
                >
                  <div class="item-media-wrap">
                    <div class="item-media">
                      <img src="~/assets/images/services/04.jpg" alt="" />
                      <a href="service-single" class="abs-link"></a>
                    </div>
                  </div>
                  <div class="item-content">
                    <h3 class="entry-title">
                      <a href="service-single">Jeans</a>
                    </h3>
                    <div class="entry-content">
                      <p>
                        Fugit legere propriae ex qui, ut eos unum senserit.
                        Nullam reprehendunt sit id, wisi facilisis
                        necessitatibus ad vix. No eruditi expetenda qui, nulla
                        iriure.
                      </p>
                    </div>
                  </div>
                </article>
              </div>
              <div class="isotope-item col-xs-12 col-sm-6">
                <article
                  class="vertical-item service-item content-padding big-padding with_shadow text-center"
                >
                  <div class="item-media-wrap">
                    <div class="item-media">
                      <img src="~/assets/images/services/05.jpg" alt="" />
                      <a href="service-single" class="abs-link"></a>
                    </div>
                  </div>
                  <div class="item-content">
                    <h3 class="entry-title">
                      <a href="service-single">Bed-linen</a>
                    </h3>
                    <div class="entry-content">
                      <p>
                        Aliquip indoctum voluptatibus at vim, vel id nonumy
                        conceptam efficiendi. Cu autem assum tacimates eos, cu
                        per indoctum molestiae ridens admodum officiis.
                      </p>
                    </div>
                  </div>
                </article>
              </div>
              <div class="isotope-item col-xs-12 col-sm-6">
                <article
                  class="vertical-item service-item content-padding big-padding with_shadow text-center"
                >
                  <div class="item-media-wrap">
                    <div class="item-media">
                      <img src="~/assets/images/services/06.jpg" alt="" />
                      <a href="service-single" class="abs-link"></a>
                    </div>
                  </div>
                  <div class="item-content">
                    <h3 class="entry-title">
                      <a href="service-single">Underwear</a>
                    </h3>
                    <div class="entry-content">
                      <p>
                        No qui ocurreret splendide temporibus, ferri augue pro
                        cu. Et ceteros aliquando usu, cu usu facer oblique, pri
                        no illud conceptam adipiscing vel eleifend qualisque.
                      </p>
                    </div>
                  </div>
                </article>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <gallery-scroll />
  </main>
</template>
<script>
import GalleryScroll from '@/components/gallery_scroll.vue'
export default {
  components: {
    GalleryScroll,
  },
}
</script>
