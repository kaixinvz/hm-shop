<template>
	<view class="plot">
		<view>
		  <image class="logo" src="/static/2故事汇广告.jpg"></image>
		</view>
		<view class="content" @click="indexDetail">
			<view class="cont-left">
				<view class="left1">全省见义勇为英雄模范《每周一星》 --贾子腾</view>
				<view class="left2">2020-12-28 16:21</view>
			</view>
			<view class="cont-right">
				<image class="right1" src="/static/2故事汇每周.jpg"></image>
			</view>
		</view>
		<view class="content">
			<view class="cont-left">
				<view class="left1">全省见义勇为英雄模范《每周一星》 --贾子腾</view>
				<view class="left2">2020-12-28 16:21</view>
			</view>
			<view class="cont-right">
				<image class="right1" src="/static/2故事汇每周.jpg"></image>
			</view>
		</view>
		<view class="content">
			<view class="cont-left">
				<view class="left1">全省见义勇为英雄模范《每周一星》 --贾子腾</view>
				<view class="left2">2020-12-28 16:21</view>
			</view>
			<view class="cont-right">
				<image class="right1" src="/static/2故事汇每周.jpg"></image>
			</view>
		</view>
		<view class="content">
			<view class="cont-left">
				<view class="left1">全省见义勇为英雄模范《每周一星》 --贾子腾</view>
				<view class="left2">2020-12-28 16:21</view>
			</view>
			<view class="cont-right">
				<image class="right1" src="/static/2故事汇每周.jpg"></image>
			</view>
		</view>
	</view>
</template>

<script>
	export default{
		methods:{
			indexDetail(){
						   uni.navigateTo({
						   	 url:'../indexDetail/indexDetail'
						   })
			}
		}
	}
</script>

<style lang="scss">
	.logo {
		width: 750rpx;
		height: 400rpx;
	}
	.content{
		width: 90%;
		margin: 0 auto;
		display: flex;
		height: 200rpx;
		padding-top:30rpx;
		border-top:1px solid #cccccc ;
		margin-top: 30rpx;
		.cont-left{
			width:80%;
			margin-right:8rpx;
			.left1{
				font-size: 18px;
			}
			.left2{
				margin-top: 60rpx;
				font-size: 14px;
			}
		}
		.cont-right{
			
			.right1{
				width:200rpx;
				height:200rpx;
				border-radius: 20rpx;
			}
			
		}
	}
</style>
