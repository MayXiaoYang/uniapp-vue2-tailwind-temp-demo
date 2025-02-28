<template>
	<view class="flex flex-col space-y-6 mx-auto items-center">
		<view>
			<image class="w-20 h-20" src="/static/logo.png"></image>
		</view>

		<view class="">
			<text class="bg-red-300 text-white">{{ title }}</text>
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

<style></style>
