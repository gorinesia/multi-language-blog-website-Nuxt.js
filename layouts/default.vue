<template>
  <div>
    <top-header />
    <main id="main" role="main">
      <Nuxt />
    </main>
    <buttom-footer />
  </div>
</template>

<script>
import TopHeader from '~/components/TopHeader.vue'
import BottomFooter from '~/components/BottomFooter.vue'

export default {
  components: {
    TopHeader,
    BottomFooter
  }
}
</script>

<style lang="scss">
@import '../assets/scss/styles.scss';
</style>
