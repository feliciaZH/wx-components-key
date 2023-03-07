<template>
<uni-shadow-root class="hello-index"><view>
  <view v-for="(item,index) in (list)" :key="item.index">{{list}}</view>
</view></uni-shadow-root>
</template>

<script>

global['__wxVueOptions'] = {components:{}}

global['__wxRoute'] = 'hello/index'
Component({
  options: {
      addGlobalClass: true
  },
  properties: {
      list: {
          type: Array,
          value: []
      }
  }
});
export default global['__wxComponents']['hello/index']
</script>
<style platform="mp-weixin">

</style>