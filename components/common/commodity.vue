<template>
	<veiw class="commodity">
		<!-- 单个商品 -->
	
		<view class="commodity-item"  v-for="(item,index) in dataList" :key="index">
			<image class="commodity-img" :src="item.imgUrl"></image>
			<view class="commodity-content">
				<text class="commodity-name"></text>
				<view>
					<text class="old-price">{{item.oprice}}</text>
					<text class="new-price">{{item.pprice}}</text>
				</view>
				<text class="discount">{{item.discount}}</text>
			</view>
		</view>
	</veiw>
</template>

<script>
	export default{
		props:{
			dataList:Array
		}
	}
</script>

<style scoped>
.commodity {
	display: flex;
	flex-wrap: wrap;
}
.commodity-item {
	width: 375rpx;
	padding-bottom: 20rpx;
}
.commodity-img {
	width: 100%;
	height: 375rpx;
}
.commodity-content {
	text-align: center;
}
.commodity-name {
	overflow: hidden;
	text-overflow: ellipsis;
	color: #333333;
	word-break: break-all;
	display: -webkit-box;
	-webkit-line-clamp: 2;
	-webkit-box-orient: vertical;
	padding: 6rpx 20rpx;
}
.old-price{

}
.new-price{
	text-decoration: line-through;
	font-size: 24rpx;
		color: #999999;
}
.discount{
	border-radius: 4rpx;
	border:  1px solid red;
	
	font-size: 20rpx;
	color: red;
	padding: 2rpx ;
	
}
</style>
