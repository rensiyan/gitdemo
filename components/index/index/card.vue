<template>
	<view cass="card">
		<slot>
			<view class="card-item">{{cardTitle}}</view>
		</slot>
		
	</view>	
</template>

<script>
	export default{
		props:{
			cardTitle:String
		}
	}
</script>

<style scoped>
	.card{
		display: flex;
		padding: 20rpx 0;
		justify-content: center;
		font-weight: bold;
	}
	.card-item{
		padding:  0 20rpx;
		font-size: 32rpx;
	}
</style>