<template>
  <div>
    Welcome
  </div>
</template>

<script>
import hub from '../utils/hub.js'
export default {
  name: 'Welcome',
  created() {
    hub.$emit('saveNavState', '')
  }
}
</script>

<style lang="less" scoped></style>
