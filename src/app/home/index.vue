<template>
    <div style="height:100%;">
        <view-box ref="viewBox">
            <x-header slot="header" style="width:100%;position:absolute;left:0;top:0;z-index:100;"></x-header>
            <router-view>11</router-view>
            <tabbar slot="bottom"></tabbar>
        </view-box>
    </div>
</template>
<script>
import { XHeader, ViewBox,Tabbar } from 'vux'

export default {
    components: {
      XHeader,
      Tabbar,
      ViewBox
      // 需要什么import引入然后加入组件的components里就好了
    }
}
</script>

