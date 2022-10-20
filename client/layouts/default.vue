<template>
  <div class="container">
    <div class="p-3">
      <Logo />
      <TopMenu />
      <Nuxt />
      <Footer />
    </div>
  </div>
</template>

<script>
import TopMenu from '~/components/TopMenu.vue'
import Footer from '~/components/Footer.vue'
export default {
  layout: 'homepage',
  components: { TopMenu, Footer },
}
</script>