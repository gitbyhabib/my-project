<template>
  <view class="content">
    <image class="logo" src="/static/logo.png"></image>
    <view>
      <text class="title">{{ title }}</text>

      <navigator class="navigator navigate" url="/pages/index/change2">
        <button type="default">change page</button>
      </navigator>
    </view>
  </view>
</template>

<script>
export default {
  data() {
    return {
      title: "Hello From test page3",
    };
  },
  onLoad() {},
  methods: {},
};
</script>

<style>
.content {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
}

.logo {
  height: 200rpx;
  width: 200rpx;
  margin: 200rpx auto 50rpx auto;
}

.text-area {
  display: flex;
  justify-content: center;
}

.title {
  font-size: 36rpx;
  color: #8f8f94;
}
</style>