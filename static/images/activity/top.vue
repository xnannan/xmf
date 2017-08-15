<template>
	<div class="">
		<div class="top">
			<ul>
				<li><img src="../../../static/images/jt.jpg" alt="" /><a href="javascript:history.back(-1)">返回</a></li>
				<li><p>活动页面</p></li>
				<li><img src="../../../static/images/dian.jpg" alt="" /></li>
			</ul>
		</div>
	</div>
</template>
<script>
	export default {
		
	}
</script>
<style scoped>
     *{
		box-sizing: border-box;
		text-decoration: none;
	}
	.top{
		width: 100%;
		padding: 0.3rem 0.2rem;
		background: #2e2d33;
	}
	.top ul{
		width: 100%;
		display: flex;
		justify-content: space-between;
		align-items: center;
		list-style: none;
	}
	.top ul li{
		color:#fff;
	}
	.top ul li:nth-of-type(1) img{
		width: 0.8rem;
		height:1.2rem;
		vertical-align:middle;
	}
	.top ul li p{
		font-weight: bold;
		font-size: 0.8rem;
	}
	.top ul li:nth-of-type(1) a{
		color:#fff;
		font-size: 0.8rem;
		margin-left: 0.3rem;
	}
</style>