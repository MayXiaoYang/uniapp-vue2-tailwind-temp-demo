<template>
	<view class="flex flex-col space-y-6 mx-auto items-center mt-7">
		<view>
			<image class="w-20 h-20" src="/static/logo.png"></image>
		</view>

		<view class="title">
			<text class="text-white text-3xl">{{ title }}</text>
		</view>
		
		<view class="notice-bar">
			<u-notice-bar text="一曲肝肠断,天涯何处觅知音."></u-notice-bar>
		</view>
	</view>
</template>

<script>
export default {
	data() {
		return {
			title: 'Hello'
		}
	},
	onLoad() {

	},
	methods: {

	}
}
</script>

<style lang="scss">
.title {
	background-color: orange;
}
.notice-bar {
	background-color: red;
}
</style>
