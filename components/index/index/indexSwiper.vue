<template>
	<swiper :indicator-dots="true" :autoplay="true" :interval="3000" :duration="1000">
		<swiper-item>
			<view class="swiper-item">
				<image class="image" src="../../../static/images/banner1.webp" mode=""></image>
			</view>
		</swiper-item>
		<swiper-item>
			<view class="swiper-item">
				<image class="image" src="../../../static/images/banner2.webp" mode=""></image>
			</view>
		</swiper-item>
		<swiper-item>
			<view class="swiper-item">
				<image class="image" src="../../../static/images/banner3.webp" mode=""></image>
			</view>
		</swiper-item>
	</swiper>
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
	swiper{
		width: 100%;
		height: 400rpx;
	}
	.image{
		width: 100%;
		height: 400rpx;
	}

</style>
