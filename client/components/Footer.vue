<template>
  <footer class="footer text-center" >
    <Logo />
    <span>Copyright &copy; 2022 d'Orellia</span>
    <nuxt-link to="/">Privacy Policy</nuxt-link>
    <nuxt-link to="/">Terms of use</nuxt-link>
    <nuxt-link to="/">Contact</nuxt-link>
  </footer>
</template>

<script>
import Logo from './Logo.vue'
export default {
  components: { Logo },
}
</script>

<style lang="scss">
.footer {
  img {
    max-height: 45px;
  }
}
</style>