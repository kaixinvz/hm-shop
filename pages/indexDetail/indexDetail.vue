<template>
	<view class="index-detail">
		<view class="text1">全国人大常委会全票表决通过烈士保护法</view>
		<view class="text2">
			<!-- <icon type="waiting" size="26" class="icon"/> -->
			2020-01-25 16:24</view>
		   <view class="page-section" style="text-align: center;">
		         <audio style="text-align:left" :src="current.src" :poster="current.poster" :name="current.name" :author="current.author" :action="audioAction" controls></audio>
		   </view>
		<view class="text3">
			<text class="tet">
				        &nbsp;&nbsp;&nbsp;&nbsp;十三届全国人大常委会第二次会议27日全票
						表决通过英雄烈士保护法，全面加强对英雄烈士的保护，维护社会公共利益，弘扬社会主义核心价值观。英烈保护法将自2018年5月1日起施行。
						  &nbsp;&nbsp;&nbsp;&nbsp;  英烈保护法明确规定，国家和人民永远
						尊崇、铭记英雄烈士为国家、人民和民族作
						出的牺牲和贡献。国家保护英雄烈士，对英
						雄烈士予以褒扬、纪念，加强对英雄烈士事
						迹和精神的宣传、教育，维护英雄烈士尊严
						和合法权益。
						&nbsp;&nbsp;&nbsp;&nbsp;英烈保护法强调，以侮辱、诽谤或者其
						他方式侵害英雄烈士的姓名、肖像、名誉、
						荣誉，损害社会公共利益的，依法承担民事
						责任;构成违反治安管理行为的，由公安机
						关依法给予治安管理处罚;构成犯罪的,依
						法追究刑事责任。
						&nbsp;&nbsp;&nbsp;&nbsp;英烈保护法还对烈士纪念日、英雄烈士
						纪念设施的保护和管理、英雄烈士抚恤优待
						制度、英雄烈士事迹和精神的宣传教育等作
						出了规定。</text>
			            </view>
    <view class="text4">来源：某某某</view>
	</view>
</template>

<script>
	export default{
		data(){
			return{
				     current:{
				           name:'政策解读',
				           author: '来自云平台',
						   src:''
				         
				       },
					     audioAction: {
					                   method: 'pause'
					               }
				    
			}
			
		}
		   
	}
</script>

<style lang="scss">
	.index-detail{
		width:90%;
		margin: 0 auto;
	}
	.text1{
		margin-top:40rpx ;
		font-size: 44rpx;
	}
	.text2{
		font-size: 20rpx;
		margin-top: 40rpx;
		margin-bottom: 40rpx;
		
		
		
		// .icon{
		// 	// width: 20rpx;
		// 	// height: 20rpx;
		// }
	}
	.text3{
		margin-top: 30rpx;
	}
	.tet{
		text-indent:40rpx; 
		font-size: 35rpx;
	}
	.text4{
		margin-top: 30rpx;
		font-size: 20rpx;
	}
</style>
