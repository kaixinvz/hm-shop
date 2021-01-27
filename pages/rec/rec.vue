<template>
	<view class="rec">
		<view>
		  <image class="logo" src="/static/4云推荐_02.gif"></image>
		</view>
		<view class="content">
			<view>
				 <text>标题 *</text>
				<input class="inpt" focus placeholder="输入文章标题" />
			</view>
			<view class="shijian">
				<text>事件描述*</text>
				<textarea  placeholder="简单描述事件过程"/>
			</view>
			<view class="shang">
				<text>上传资料*</text>
				<uploadImg ref='uploadImg' 
				       class="upload"
				      :mode="imgList" 
					  @chooseFile='chooseFile' 
					  @imgDelete='imgDelete' 
					  :control='control' 
					  :columnNum="columnNum"  />
			</view>
			<view class="shang">
				 <text>姓名 *</text>
				<input class="inpt" focus placeholder="输入姓名" />
			</view>
			<view class="shang">
				 <text>联系方式 *</text>
				<input class="inpt" focus placeholder="输入联系方式" />
			</view>
			<view class="shang-1">
				<button type="default">上传</button>
			</view>
		</view>
	</view>
</template>

<script>
	import uploadImg from "../../components/xiaohuang-uploadImg/uploadImg.vue"
	export default{
		components:{ uploadImg },
		data(){ return { control: true, columnNum: 4, imgList: [] }},
		methods:{ 
			chooseFile(list, v) 
			{ 
				console.log("上传图片_list：", list) 
				console.log("上传图片_v：", v)
		   },
		    imgDelete(list, eq) 
			{ 
				console.log("删除图片_list：", list) 
				console.log("删除图片_eq：", eq) 
			} 
		}

	}
</script>

<style>
	.logo {
		width: 750rpx;
		height: 400rpx;
	}
	.content{
		width: 90%;
		margin: 0 auto;
		margin-top: 40rpx;
	
	}
	.content input{
			background-color: #f3f3f3;
			padding:20rpx;
			height: 40rpx;
			margin-top: 20rpx;
			border-radius: 10rpx;	
	}
	.shijian{
		
		margin-top: 40rpx;
	
	}
	.shijian textarea{
		width: 95%;
		border-radius:10rpx;
		background-color: #f3f3f3;
		margin-top: 20rpx;
		padding: 20rpx;
		height: 150rpx;
	}
	.shang{
		margin-top: 40rpx;
		}
	.upload{
		margin-top: 20rpx;
		width:150%;
		height:150%;
		margin-left: 0;
	}
	.shang-1{
		margin-top: 40rpx;
	}
	.shang-1 button{
		background-color: #DD524D;
		color:#F1F1F1;
	}
</style>
