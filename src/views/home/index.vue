<!-- home -->
<template>
  <div>
    <h1>home</h1>
    <van-button type="primary">主要按钮</van-button>
  </div>
</template>

<script>
// import { api } from '@/config'
import {
  Button
} from 'vant'
export default {
  components: {
    'van-button': Button
  },

  data () {
    return {}
  },

  computed: {},

  mounted () {
    // console.log(process.env)
    console.log('hello world')
  },

  methods: {}
}

</script>
<style lang='scss' scoped>
h1 {
  background: red;
  width: 375px;
}
</style>
