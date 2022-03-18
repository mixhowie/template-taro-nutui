<template>
  <view class="header">
      <text selectable>This is Header</text>
  </view>
</template>

<script>
import { computed } from 'vue'
import { useStore } from 'vuex'

export default {
  setup () {
    const store = useStore()
    const getNumbers = computed(() => store.getters.getNumbers)

    return {
      getNumbers
    }
  }
}
</script>

<style lang='scss'>
.header {
  height: 100px;
  background: gray;
}
</style>
