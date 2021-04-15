<template>
	<div id="header">
		<div class="header-left"><i class="iconfont">&#xe667;</i></div>
		<div class="header-input">
			<input type="text" class="iconfont" placeholder=" &#xe74b; 输入城市/景点/游玩主题">
		</div>
		<div class="header-right">
			<span>城市</span>
			<i class="iconfont">&#xe62a;</i>
		</div>
	</div>
</template>
<script>

</script>
<style lang="less" scoped>
	#header {
		display: flex;
		// height: .86rem;
		line-height: .62rem;
		background: #00bcd4;
		color: #fff;
		padding: .12rem;

		.header-left {
			width: .64rem;
			float: left;
		}

		.header-input {
			flex: 1;
			margin-left: .2rem;
			input{
				width: calc(100% - 0.2rem);
				height: 100%;
				outline: none;
				border: none;
				background: #fff;
				border-radius: .1rem;
				padding-left:.2rem ;
				
			}
		}

		.header-right {
			width: 1.24rem;
			float: right;
			text-align: center;
		}
	}
</style>
