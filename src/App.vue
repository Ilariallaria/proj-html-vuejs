<template>
  <div id="app">
    <header>
    <AaHeaderTop/>
    <AbHeaderBottom/>
    </header>

    <main>
      <BaBanner1/>
      <BbSectionJournal/>
      <BcSectionPopularRecipes/>
      <BdSectionCulinaryCollection/>
      <BeSectionFarm/>
      <BfBanner2/>
      <BgSectionGallery/>
    </main>

    <footer>
      <CaFooterTop/>
    </footer>


  </div>
</template>

<script>
import AaHeaderTop from './components/AaHeader/AaHeaderTop.vue'
import AbHeaderBottom from './components/AaHeader/AbHeaderBottom.vue'
import BaBanner1 from './components/BaMain/BaBanner1.vue'
import BbSectionJournal from './components/BaMain/BbSectionJournal.vue'
import BcSectionPopularRecipes from './components/BaMain/BcSectionPopularRecipes.vue'
import BdSectionCulinaryCollection from './components/BaMain/BdSectionCulinaryCollection.vue'
import BeSectionFarm from './components/BaMain/BeSectionFarm.vue'
import BfBanner2 from './components/BaMain/BfBanner2.vue'
import BgSectionGallery from './components/BaMain/BgSectionGallery.vue'
import CaFooterTop from './components/CaFooter/CaFooterTop.vue'

export default {
  name: 'App',
  components: {
    AaHeaderTop,
    AbHeaderBottom,
    BaBanner1,
    BbSectionJournal,
    BcSectionPopularRecipes,
    BdSectionCulinaryCollection,
    BeSectionFarm,
    BfBanner2,
    BgSectionGallery,
    CaFooterTop,
  }
}
</script>

<style lang="scss">
@import './style/commons';



</style>
