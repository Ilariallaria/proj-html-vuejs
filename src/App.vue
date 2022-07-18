<template>
  <div id="app">
    <header>
    <AaHeaderTop/>
    <AbHeaderBottom/>
    </header>

    <main>
      <MyBanner/>
    </main>


  </div>
</template>

<script>
import AaHeaderTop from './components/AaHeaderTop.vue'
import AbHeaderBottom from './components/AbHeaderBottom.vue'
import MyBanner from './components/MyBanner.vue'

export default {
  name: 'App',
  components: {
    AaHeaderTop,
    AbHeaderBottom,
    MyBanner,
  }
}
</script>

<style lang="scss">
@import './style/commons'
</style>
