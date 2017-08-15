<template>
	<div class="lingqu-wrapper">
		<div class="con">
			<img src="../../../static/images/hongbao.png" />	
		</div>
		
		<div class="shuru">
			<input type="text" placeholder="请输入您的手机号码" />
		</div>
		
		<!--路由连接-->
		<router-link to="">
			<div class="ling">
				<img src="../../../static/images/lingqu.png" />
			</div>
		</router-link>
		
		<div class="foot">
			<img src="../../../static/images/footlogo.png" />
		</div>
	</div>
</template>

<script>
</script>

<style scoped> 
.con{
	position: relative;
}
.con img{
		width: 16rem;
	}
.shuru{
	width: 12.25rem;
	height: 1.85rem;
	border: 1px solid #cacaca;
	margin: 0 auto;
	border-radius: 1rem;
	margin-top:1rem ;
	
}
.shuru input{
	font-size: 0.6rem;
	width: 100%;
	height: 100%;
	text-align: center;
	line-height: 50%;
}
.ling{
	width: 12.25rem;
	margin: 1rem auto;
	
}
.ling img{
	width: 12.25rem;
}
.foot{
	text-align: center;
	line-height:2rem ;
}
.foot img{
	width: 4.15rem;
}
</style>