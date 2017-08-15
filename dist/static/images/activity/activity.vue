<template>
	<div class="activity-wrapper">
		<div id="bg"></div>
		
		<!--路由链接-->
		<router-link to="/activityIn">
			<div id="in"></div>
		</router-link>
		
	</div>
</template>

<script>
</script>

<style scoped>
.activity-wrapper {		
		height: 26rem;
		position: relative;
	}
#bg{
	width: 16rem;
	background: green;
	height: 28.5rem;
	background:url(../../../static/images/bander.png) no-repeat;
	background-size:100% 100%;
}
#in{
		width: 8.1rem;
		height: 2.6rem;
		position: absolute;
		bottom:0.35rem ;
		left:3.9rem;
		/*background: pink;*/
	}
</style>