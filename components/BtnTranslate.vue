<template>
  <button @click='showLangMenu'>
    <HeroIconOutlineTranslate class='h-6 w-6' />
  </button>
</template>

<script>
import HeroIconOutlineTranslate from '~/components/HeroIconOutlineTranslate'

export default {
  name: 'BtnTranslate',
  components: { HeroIconOutlineTranslate },
  methods: {
    showLangMenu() {
      this.$store.dispatch('lang/TOGGLE_SHOW')
    }
  }
}
</script>

<style scoped>

</style>
