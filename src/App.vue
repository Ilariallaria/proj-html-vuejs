<template>
  <div id="app">
    <header>
    <AaHeaderTop/>
    <AbHeaderBottom/>
    </header>

    <main>
      <MyBanner1/>
      <BaMainJournal/>
    </main>


  </div>
</template>

<script>
import AaHeaderTop from './components/AaHeaderTop.vue'
import AbHeaderBottom from './components/AbHeaderBottom.vue'
import MyBanner1 from './components/MyBanner1.vue'
import BaMainJournal from './components/BaMainJournal.vue'

export default {
  name: 'App',
  components: {
    AaHeaderTop,
    AbHeaderBottom,
    MyBanner1,
    BaMainJournal,
  }
}
</script>

<style lang="scss">
@import './style/commons'
</style>
