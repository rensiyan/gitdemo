<template>
	<view class="recommond bg-color">
		<view class="recommond-item">
			<image class="item-big" src="../../../static/images/image3.jpg" mode=""></image>
			<view class="item-small">
				<image class="item-img" src="../../../static/images/group1.png"></image>
				<image class="item-img" src="../../../static/images/group2.png"></image>
				<image class="item-img" src="../../../static/images/group3.png"></image>
			</view>
		</view>
		<view class="recommond-item">
			<image class="item-big" src="../../../static/images/image3.jpg" mode=""></image>
			<view class="item-small">
				<image class="item-img" src="../../../static/images/group1.png"></image>
				<image class="item-img" src="../../../static/images/group2.png"></image>
				<image class="item-img" src="../../../static/images/group3.png"></image>
			</view>
		</view>
		<view class="recommond-item">
			<image class="item-big" src="../../../static/images/image3.jpg" mode=""></image>
			<view class="item-small">
				<image class="item-img" src="../../../static/images/group1.png"></image>
				<image class="item-img" src="../../../static/images/group2.png"></image>
				<image class="item-img" src="../../../static/images/group3.png"></image>
			</view>
		</view>
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

<style scoped>
	.recommond {
		padding: 20rpx;
		width: 100%;
	}

	.recommond-item {
		display: flex;
		flex-direction: column;
		border-radius: 20rpx;
		border: 2rpx solid #CCCCCC;
		overflow: hidden;
		margin: 20rpx 0;
	}

	.item-big {
		width: 100%;
		height: 300rpx;
	}
	.item-small{
		width: 100%;
		height: 240rpx;
	}
	.item-img{
		width: 33.333%;
		height:240rpx;
	}
</style>