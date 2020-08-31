<template>
	<view class="container">
		<!--  使用 web-view 映射自己的自定义 html -->
		<web-view src="../../static/index.html"></web-view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
			}
		},
		methods: {

		}
	}
</script>

<style>
	.container {
		padding: 20px;
		font-size: 14px;
		line-height: 24px;
	}
</style>
