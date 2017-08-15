<template>
	<div class="activityIn-wrapper">
		<headers></headers>
		<div class="activityIn-wrapper-top">
			<img src="../../../static/images/banner.png" />
		</div>
		
		<router-link to="/one">
			<div class="btn">
				立即测试
			</div>
		</router-link>
		
		<div class="lulu">
			<img src="../../../static/images/lulu.png" />
			<div class="content">
				<p v-for=" c in guoze"><span>{{c.num}}</span>{{c.con}}</p>
			</div>
			
			<div class="down">
				<img src="../../../static/images/footlogo.png" />
			</div>
			
		</div>
		
		<div class="foot">
			<img src="../../../static/images/foot.png"/>
			
			<!--路由连接-->
			<router-link to="">
				<div class="deng">
					立即下载
				</div>
			</router-link>
		</div>
	</div>
</template>

<script>
import headers from '@/components/activity/top'

	export default{
		data(){
			return{
				guoze:[
					{'num':'1.','con':'本测试共5小题，每小题20分，共100分。'},
					{'num':'2.','con':'每题给出的三个选项中，只有一项最符合题目要求。'},
					{'num':'3.','con':'每个账户只有一次领取奖励的机会，千万别手滑哦，偷偷告诉你，分享后领奖机会+1'},
					{'num':'*','con':'本活动最终解释归北京蜜蜂出行科技有限公司所有'}
				]
			}
		},
		components:{
			headers
		}
	}
</script>

<style scoped>
.activityIn-wrapper{
	position: relative;
}
.activityIn-wrapper-top img{
	width:16rem ;
}	
.btn{
	width: 12.5rem;
	line-height: 2.05rem;
	margin: 0 auto;
	background: #ffe12e;
	font-size:0.65rem ;
	font-weight: bold;
	text-align: center;
	border-radius: 1rem;
	
}
.lulu{
	border-top:1px solid #ededed;
	margin-top: 1.2rem;
	padding-top: 1rem;
}
.lulu img{
	width:16rem;
}
.content{
	padding: 0.9rem;
	
}
.content p{
	font-size: 0.55rem;
}
.down{
	width: 4.1rem; 
	margin: 0 auto;
	margin-top: 1.5rem;
}
.down img{
	width: 4.1rem;
}
.foot{
	position: absolute;
	bottom: 0;
}
.foot img{
	width:16rem ;
	
} 
.deng{
	width: 3.3rem;
	line-height: 1.15rem;
	border:1px solid #cdb52f;
	position: absolute;
	right: 1rem;
	top: 0.5rem;
	text-align: center;
	border-radius: 1rem;
	font-size: 0.35rem;
	color: #585035;
}
</style>