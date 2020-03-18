<template>
	<view>
		H5. Test showToast
	</view>
</template>

<script>
	export default {
		data() {
			return {
			}
		},
		onLoad: function () {
			uni.showToast({
				title: '账户登录信息已失效,请重新登录',
				icon: 'none',
				duration: 2000,
				success: function(){  
					uni.reLaunch({  
						url: '../main/start',
					});  
				}
			});
			return;
		}
	}
</script>