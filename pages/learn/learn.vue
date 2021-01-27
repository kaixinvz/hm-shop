<template>
	<view>
		<view class="learn-1">
			<uni-search-bar
				placeholder="输入搜索关键字" 
				@confirm="search"
				:radius="100"
				></uni-search-bar>
		</view>
		<view class="learn-2">
			<view class="contt">
				<view class="cont-left">那些行为可以确认为见义勇为的行为?</view>
				<view class="cont-right">2020-12-25 14:54</view>	
			</view>
			<view class="contt">
				<view class="cont-left">那些行为可以确认为见义勇为的行为?</view>
				<view class="cont-right">2020-12-25 14:54</view>	
			</view>
			<view class="contt">
				<view class="cont-left">那些行为可以确认为见义勇为的行为?</view>
				<view class="cont-right">2020-12-25 14:54</view>	
			</view>
			<view class="contt">
				<view class="cont-left">那些行为可以确认为见义勇为的行为?</view>
				<view class="cont-right">2020-12-25 14:54</view>	
			</view>
			<view class="contt">
				<view class="cont-left">那些行为可以确认为见义勇为的行为?</view>
				<view class="cont-right">2020-12-25 14:54</view>	
			</view>
			<view class="contt">
				<view class="cont-left">那些行为可以确认为见义勇为的行为?</view>
				<view class="cont-right">2020-12-25 14:54</view>	
			</view>
		</view>
	</view>
</template>

<script>
</script>

<style lang="scss">
    .learn-1{
		margin-top:10rpx;
		height: 50rpx;
	}
	.learn-2{
		width: 100%;
		background-color:#f7f7f7;
		margin-top: 60rpx;
	}
	.contt{
		margin:30rpx auto;
		width: 90%;
		height: 150rpx;
	    background-color: #ffffff;
		.cont-left{
			padding-top:25rpx;
			padding-left:30rpx;
			font-size: 18px;
		}
		.cont-right{
			font-size: 14px;
			color:#848484;
			padding-left: 30rpx;
			padding-top: 25rpx;
		}
		// .bar{
	 //      outline-style:none;
		// }
	}
</style>
