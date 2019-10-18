<template>
  <div>
    <van-button type="info">信息按钮</van-button>
  </div>
</template>

<script>
import { Button } from 'vant'
export default {
  name: 'test',
  data () {
    return {

    }
  },
  components: {
    [Button.name]: Button
  }
}
</script>

<style scoped lang="less">
</style>
