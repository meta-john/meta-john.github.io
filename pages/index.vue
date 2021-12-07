<template>
  <div>
    <SiteNav />
    <SHero />
    <SFeatures />
    <SSplit />
    <SDeploy />
    <SStats />
    <SiteFooter />
  </div>
</template>

<script>
import SiteNav from '~/components/SiteNav'
import SHero from '~/components/SHero'
import SStats from '~/components/SStats'
import SFeatures from '~/components/SFeatures'
import SDeploy from '~/components/SDeploy'
import SSplit from '~/components/SSplit'
import SiteFooter from '~/components/SiteFooter'
export default {
  components: { SiteFooter, SSplit, SDeploy, SFeatures, SStats, SHero, SiteNav }
}
</script>
