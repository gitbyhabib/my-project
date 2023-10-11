<template>
  <view>
    <text>{{ textvalue }}</text
    ><!-- 这里演示了组件值的绑定 -->
    <button :type="buttontype" @click="changetextvalue()">修改为789</button
    ><!-- 这里演示了属性和事件的绑定 -->

    <navigator class="navigator navigate" url="/pages/index/change3">
      <button type="default">change to page3</button>
    </navigator>
  </view>
</template>  
	<script>
export default {
  data() {
    return {
      textvalue: "123",
      buttontype: "primary",
    };
  },
  onLoad() {
    this.textvalue = "456"; //这里修改textvalue的值，其实123都来不及显示就变成了456
  },
  methods: {
    changetextvalue() {
      this.textvalue = "789"; //这里修改textvalue的值，页面自动刷新为789
    },
  },
};
</script>