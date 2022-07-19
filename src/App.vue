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
    </main>


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
  }
}
</script>

<style lang="scss">
@import './style/commons';



</style>
