<template>
	<!--个人中心-关系族谱-空白页-->
	<div class="family_tree_blank">
		<div class="hea">
			<router-link to="" tag="p"><i class="iconfont">&#xe646;</i></router-link>
			<p>关系族谱</p>
		</div>
		<router-link to="/family_tree" tag="div" class="null">
			<img src="../../build/empty.png"/>
		</router-link>
	</div>
</template>

<script>
</script>

<style>
	*{
		margin: 0;
		padding: 0;
		border: 0;
		outline: none;
		vertical-align:baseline;
	}
	img{
		border: none;
	}
	a{
		text-decoration: none;
	}
	li{
		list-style: none;
	}
	.family_tree_blank{
		width: 100%;
	}
	.hea{
		width: 100%;
		height: 3.5rem;
		border-bottom: 1px solid #F0F0F0;
	}
	.hea>p{
	    height: 3.5rem;
	    line-height: 3.5rem;
	    text-align: center;
	    float: left;
	}
	.hea>p:first-child{
		width: 10%;
	}
	.hea>p:nth-child(2){
		width: 25%;
	    margin-left: 26%;
	    font-size: 15px;
	}
	.null{
		width: 60%;
		height: 15rem;
		margin: auto;
		margin-top: 40%;
	}
	.null>img{
		width: 100%;
		height: 100%;
	}
</style>