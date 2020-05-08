<template>
  <view class="content"></view>
</template>

<script>
  import utils from '@/utils/utils.js';
  export default {
    data() {
      return {

      }
    },
    onLoad() {
      console.log(utils.utcToBeijing('2020-05-08T04:25:44.000Z')); // 2020/05/08 12:25
    },
    methods: {

    }
  }
</script>

<style>
  
</style>
