<template>
	<div class="getit-wrapper">
		<headers></headers>
		<div class="top">
			<img src="../../../static/images/ok.png" />
			<p>领取成功</p>
		</div>
		<div class="center">
			<img src="../../../static/images/youhuijuan.png" />
		</div>
		<div class="con">
			<p>
			<span>3</span>
			元出行券已经放入您的账户钱包中，马上分享，邀请好友一起来股份吧！
			</p>
		</div>
		
		<!--路由链接-->
		<router-link to="">
			<div class="last">
				立即分享
			</div>
		</router-link>
		
	</div>
</template>

<script>
import headers from '@/components/activity/top'
	export default{
		components:{
			headers
		}
	}

</script>

<style scoped>
.top{
	text-align: center;
	padding-top: 1.45rem;
	/*background: pink;*/
}
.top img{
	width: 4.45rem;
}
.top p{
	font-size: 0.8rem;
	color: #333333;
	margin-top: 0.6rem;
}
.center img{
	width: 16rem;
}
.con{
	font-size: 0.65rem;
	padding:1.7rem 0;
	/*background: pink;*/
}
.con p{
	width: 11.25rem;
	margin: 0 auto;
}
.con span{
	color: #ff0200;
}
.last{
	width: 10.9rem;
	line-height: 2.35rem;
	background: #ffe12e;
	font-size: 0.85rem;
	border-radius: 2rem;
	text-align: center;
	color: #323431;
	margin: 2rem auto;
	
}
</style>