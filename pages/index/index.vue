<template>
	<view class="content">
		<view>
		  <image class="logo" src="/static/1政策云广告.jpg"></image>
		</view>
		<view class="tiei">
			<view class="tili">见义勇为保障条例解读</view>
		</view>
		<view class="line"></view>
		<view class="cont" @click="indexDetail">
			<view class="con-left">
					<view>
						<view class="date1">2018</view>
						<view class="date2">02-08</view>
					</view>
					<view class="date">——</view>
					<view class="date3">11.31</view>
			
			</view>
			<view class="cont-right">
				全国人大常委会全票表决通过英雄烈士保护法
			</view>
		</view>
		<view class="cont" @click="indexDetail">
			<view class="con-left">
					<view>
						<view class="date1">2018</view>
						<view class="date2">02-08</view>
					</view>
					<view class="date">——</view>
					<view class="date3">11.31</view>
			
			</view>
			<view class="cont-right">
				全国人大常委会全票表决通过英雄烈士保护法
			</view>
		</view>
		<view class="cont" @click="indexDetail">
			<view class="con-left">
					<view>
						<view class="date1">2018</view>
						<view class="date2">02-08</view>
					</view>
					<view class="date">——</view>
					<view class="date3">11.31</view>
			
			</view>
			<view class="cont-right">
				全国人大常委会全票表决通过英雄烈士保护法
			</view>
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
           indexDetail(){
			   uni.navigateTo({
			   	 url:'../indexDetail/indexDetail'
			   })
		   }
		}
	}
</script>

<style lang="scss">
	.ente{
		height: 100%;
	}
	.content {
		display: flex;
		flex-direction: column;
		align-items: center;
		justify-content: center;
	}
	.logo {	
		width: 750rpx;
		height: 400rpx;
	}
	.tiei{
		width: 100%;
		display: flex;
	
		.tili{
            margin: 0 auto;			
			width: 90%;
			height: 100rpx;
			text-align: center;
			line-height: 100rpx;
			color: white;
			border-radius: 50rpx;
			background-color: #DD524D;	
			margin-top: 20rpx;
			font-weight: 400;
		}
	}
	.line{
		width: 90%;
		margin-top:30rpx;
		border:0.1px solid #cccccc;
	}
	.cont{
		width: 90%;
		height: 170rpx;
		border: 4px solid #dddddd;
		margin-top: 30rpx;
		border-radius: 30rpx;
		display: flex;
		.con-left{
			width: 20%;
			margin-left: 36rpx;
			font-weight: 300;
			text-align: center;
			.date1{
				background-color: #c8000d;
				color:white;
			}
			.date2{
				background-color: #ec525e;
				color:white;
			}
			.date{
				color:#ccc
				
			}
		}
		.cont-right{
			margin-top:10rpx;
			margin-left: 10rpx;
		}
	}
	
</style>
