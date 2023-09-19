<template>
	<view class="content">
		<!-- <image class="logo" src="/static/logo.png"></image> -->

		<!-- 		<view class="wx-nav">
			<view class="iconfont icon-ai219"></view>
			<text>向前看</text>
			<view class="iconfont icon-xiaoxi"></view>
		</view> -->

		<!-- <indexSwiper></indexSwiper>
		<recommond></recommond>
		<card cardTitle="猜你喜欢"></card>
		<commodityList></commodityList> -->
		<banner></banner>
		<Icon></Icon>
	</view>
</template>

<script>
import indexSwiper from '@/components/index/index/indexSwiper.vue';
import recommond from '@/components/index/index/recommond.vue';
import card from '../../components/index/index/card.vue';
import commodityList from '../../components/common/commodityList.vue';
import banner from "../../components/index/index/banner.vue"
import Icon  from "../../components/index/index/icon.vue"
export default {
	components: {
		indexSwiper,
		recommond,
		card,
		commodityList,
		banner,
		Icon
	},
	data() {
		return {};
	},
	onLoad() {},
	methods: {}
};
</script>

<style scoped>
.wx-nav {
	text-align: center;
	height: 200rpx;
	width: 100%;
	line-height: 200rpx;
	display: flex;
	justify-content: space-between;
	align-items: center;
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
	margin-top: 200rpx;
	margin-left: auto;
	margin-right: auto;
	margin-bottom: 50rpx;
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
