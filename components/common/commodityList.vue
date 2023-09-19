<template>
	<view>
		<!-- 单个商品列表 -->
		<commodity :dataList="commodityList"></commodity>
	</view>
</template>

<script>
	
	import commodity from "./commodity.vue"
	export default {
		components:{
			commodity,
		},
		data(){
			return{
				commodityList:[
					{
						id:1,
						imgUrl:"../../static/images/clothes1.webp",
						name:"理性购物，快乐购物888哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈",
						pprice:"￥888",
						oprice:"￥666",
						discount:"8.8折"
					},
					{
						id:2,
						imgUrl:"../../static/images/clothes2.webp",
						name:"理性购物，快乐购物888哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈",
						pprice:"￥888",
						oprice:"￥666",
						discount:"8.8折"
					},
					{
						id:3,
						imgUrl:"../../static/images/clothes3.webp",
						name:"理性购物，快乐购物888哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈",
						pprice:"￥888",
						oprice:"￥666",
						discount:"8.8折"
					},
					{
						id:4,
						imgUrl:"../../static/images/clothes4.webp",
						name:"理性购物，快乐购物888哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈哈",
						pprice:"￥888",
						oprice:"￥666",
						discount:"8.8折"
					}
				]
			}
		}
	}
</script>

<style scoped>
	
</style>
