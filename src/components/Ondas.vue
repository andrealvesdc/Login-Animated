<template>
    <div class="ondas">
        <section>
		    <div class="wave"> </div>
	    </section>
    </div>
</template>

<script>
export default {

}
</script>

<style>
body{
	margin: 0;
	padding: 0;
}
section{
	position: end;
	width: 100%;
	height: 100vh;
	background-color: rgb(34, 130, 175);
	background-size: cover;
	background-attachment: fixed;
}
section .wave{
	position: absolute;
	width: 100%;
	height: 143px;
	bottom: 0;
	left: 0;
	background-image: url(wave.png);
	animation: animate 10s linear infinite; 
} 
section .wave:before{
	content: '';
	width: 100%;
	height: 143px;
	background: url(wave.png);
	position: absolute;
	top: 0;
	left: 0;
	opacity: 0.4;
	animation: animate-reverse 10s linear infinite;
} 
section .wave:after{
	content: '';
	width: 100%;
	height: 143px;
	background: url(wave.png);
	position: absolute;
	top: 0;
	left: 0;
	opacity: 0.4;
	animation-delay: -5s;
	animation: animate-reverse 20s linear infinite;
} 
@keyframes animate{
	0%
	{
		background-position: 0;
	}
	100%{
		background-position: 1360px;
	}
}
@keyframes animate-reverse{
	0%
	{
		background-position: 1360px;
	}
	100%{
		background-position: 0px;
	}
}
</style>
