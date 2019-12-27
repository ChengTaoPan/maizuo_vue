<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <van-image
      width="100"
      height="100"
      src="https://img.yzcdn.cn/vant/cat.jpeg"
    />
    <van-button type="default">默认按钮</van-button>
    <van-button type="primary">主要按钮</van-button>
    <van-button type="info">信息按钮</van-button>
    <van-button type="warning">警告按钮</van-button>
    <van-button type="danger">危险按钮</van-button>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'

import Vue from 'vue'
import { Image, Button } from 'vant'

Vue.use(Button)
Vue.use(Image)
export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
