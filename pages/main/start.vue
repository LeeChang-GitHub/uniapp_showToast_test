<template>
	<view>
		<button @click="startLogin()"> 登 录</button>
	</view>
</template>
<script>
	export default {
		methods: {
		    startLogin(){
				uni.reLaunch({
					url: '../main/test',
				});
		    }
		}
	}
</script>
