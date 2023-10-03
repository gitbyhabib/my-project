<template>
	<view class="content">
	
		<view>
		

		<navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator><navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator><navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator><navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator><navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator><navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator><navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator><navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator><navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator><navigator class="navigator navigate" url="/pages/index/change3">
	       <button type="default">change page</button>
	     </navigator>

		<!--  <navigator :url="'/window/lefttest?item=' + encodeURIComponent(JSON.stringify(item))"></navigator> -->
		</view>
		<view>
	    
	  </view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				title: 'Hello',
				data: ' I have done this in a new way',
			
			}
		},
		onLoad() {
			

		},
		methods: {

		}
	}
</script>

<style>
.list-0{
    background-color: #aaaaff;
	padding: 15px;
  }
  .list-1{
    background-color: #ffaa7f;
	padding: 15px;
  }

.text-center{
	text-align: center;
	display: flex;
	flex-direction: column;
		
}
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
