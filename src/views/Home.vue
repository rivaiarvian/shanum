<template>
  <div class="home">
    <Header />
    <Hero />
    <ProductItem />
    <InstaShanum />
    <PartnerLogo />
    <Footer />

  </div>
</template>

<script>

import Header from '@/components/Header.vue'
import Hero from '@/components/Hero.vue'
import ProductItem from '@/components/ProductItem.vue'
import InstaShanum from '@/components/InstaShanum.vue'
import PartnerLogo from '@/components/PartnerLogo.vue'
import Footer from '@/components/Footer.vue'

export default {
  name: 'home',
  components: {
    Header,
    Hero,
    ProductItem,
    InstaShanum,
    PartnerLogo,
    Footer
  }
}
</script>
