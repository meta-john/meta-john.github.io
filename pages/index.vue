<template>
  <div>
    <SHero />
    <SFeatures />
    <SSplit />
    <SDeploy />
    <SStats />
  </div>
</template>

<script>
import SHero from '~/components/SHero'
import SStats from '~/components/SStats'
import SFeatures from '~/components/SFeatures'
import SDeploy from '~/components/SDeploy'
import SSplit from '~/components/SSplit'

export default {
  components: { SSplit, SDeploy, SFeatures, SStats, SHero }
}
</script>
