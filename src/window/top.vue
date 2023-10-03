<template>  
		<view>  
			<text class="top">{{textvalue}}</text><!-- 这里演示了组件值的绑定 -->  
			
		  
		</view>  
	</template>  
	<script>  
		export default {  
			data() {  
				return {  
					textvalue:"This is the top of this page",  
					buttontype:"primary"  
				};  
			},  
			onLoad() {  
				this.textvalue="456"//这里修改textvalue的值，其实123都来不及显示就变成了456  
			},  
			methods: {  
				changetextvalue() {  
					this.textvalue="789"//这里修改textvalue的值，页面自动刷新为789  
				}  
			}  
		}  
	</script>

	<style>
	.top{
		display: flex;
		flex-direction: column;
		align-items: center;
	}
</style>