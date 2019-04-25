<template>
    <div class="cabecalho">
		<div class="nav">
			<div class="logo">
				cabeçalho
			</div>
			<div class="logo">
			</div>
		</div>
	</div>
</template>

<script>
export default {

}
</script>

<style>

html,body{
	margin: 0;
	padding: 0;
	width: 100%;
}
body{
	width: 100%;
	height: 100vh;
	font-family: sans-serif;
	background-color: none;
    
}
.nav{
	position: absolute;
	top: 0;
	left: 0;
	margin: 0;
	padding: 0;
	width: 100%;
	height: 80px;
}
.logo{
	letter-spacing: 1px;
	float: left;
	color: rgb(255, 255, 255);
	font-size: 20px;
	line-height: 80px;
	padding: 0 6em;
}
.menu{
	float: right;
	line-height: 60px;
	margin: 0 6em;
    font-size: 22px;
}
.menu ul{
	list-style: none;
}
.menu ul li{
	display: inline-block;
}
.menu ul li a{
	text-decoration: none;
	color: rgb(255, 255, 255);
	font-weight: lighter;
	padding: 0 20px;
}
.header{
	position: absolute;
	top: 20%;
	left: 50%;
	transform: translate(-50%,-50%);
	text-align: center;
	font-weight: lighter;
}
.header span{
	font-size: 52px;
	color: rgb(255, 255, 255);
	font-size: 30px;
}
.header p {
	font-size: 25px;
}
.title{
    color: rgb(255, 255, 255);
	
}


</style>
