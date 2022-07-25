<template>
  <div>
    <BaseHeader />
    <BaseMain />
    <BaseFooter />
    <BottomFooter />
  </div>

</template>

<script>
import BaseHeader from './components/BaseHeader.vue'
import BaseMain from './components/BaseMain.vue'
import BaseFooter from './components/BaseFooter.vue'
import BottomFooter from './components/BottomFooter.vue'



export default {
  name: 'App',
  components: {
    BaseHeader,
    BaseMain,
    BaseFooter,
    BottomFooter,
  }
}
</script>

<style lang="scss">
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
</style>
