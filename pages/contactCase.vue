<template>
  <div id="contact-page" class="page-wrapper contact-page content-page">
    <site-hero
      title="Contact Us"
      subtitle="Web to Case Example"
      image="/uploads/rubinCovid.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="tile is-ancestor">
          <div class="tile is-parent">
            <article class="tile is-child box">
              <p class="title">
                EFocus
              </p>
              <p class="subtitle">
                Newsletters
              </p>
              <figure class="image is-1by1 ">
                <opti-image
                  :src="require('~/assets/uploads/rubinmark.jpg').src"
                  :srcset="
                    require('~/assets/uploads/rubinmark.jpg').srcSet
                  "
                />
              </figure>
              <br />
              <div class="content">
                <p>
                  <strong>
                    05/21/2020
                  </strong>
                </p>
                <p>
COVID-19: FASB Proposes Delay For Leases And Revenue Recognition Standards For Private Companies And Not-For-Profit Organizations
                </p>
              </div>
            </article>
          </div>
          <div class="tile is-parent is-8">
            <article class="tile is-child box">
              <contact-form />
            </article>
          </div>
        </div>
      </template>
    </main-section>
  </div>
</template>
<script>
import ContactForm from '~/components/ContactFormCase'
export default {
  head() {
    return {
      title: `Contact | ${this.$siteConfig.siteName}`
    }
  },
  components: { ContactForm }
}
</script>
