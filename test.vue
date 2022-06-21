<template>
  <view>
    <camera style="height: 500px" devicePosition="back" flash="auto" class="camera" mode="scanCode" @onScanCode="scanCode"></camera>
  </view>
</template>

<script>
import Taro from '@tarojs/taro'

export default {
  name: 'ws-carema',
  methods: {
    scanCode(data) {
      console.log(data)
    },
  },
}
</script>


<!-- <style lang="scss" scoped>
@import './css/index.scss';
</style> -->
