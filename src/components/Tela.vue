<template>
    <div class="tela">
        <div>
            <form class="box" action="index.html" method="post">
            <h1>Bem-vindo aluno(a)</h1>
            <input type="text" name="" placeholder="Usuário">
            <input type="password" name="" placeholder="Senha">
            <input type="submit" name="" value="Conecte-se">
            <input type="submit" name="" value="Primeiro acesso?">
            <li><a href="#">Esqueci a senha</a></li>
            </form>
        </div>
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
  font-family: sans-serif;
  background: #ffffff;
}
.box{
  width: 300px;
  padding: 20px;
  position: absolute;
  top: 44%;
  left: 50%;
  transform: translate(-50%,-50%);
  background: #141b30;
  text-align: center;
  border-radius: 10px;
}
.box h1{
  color: white;
  font-weight: 500;
}
.box input[type = "text"],.box input[type = "password"]{
  border:0;
  background: none;
  display: block;
  margin: 20px auto;
  text-align: center;
  border: 2px solid #f8f8f8;
  padding: 14px 10px;
  width: 200px;
  outline: none;
  color: white;
  border-radius: 10px;
  transition: 0.25s;
  font-size: 16px;

}
.box input[type = "text"]:focus,.box input[type = "password"]:focus{
  width: 280px;
  border-color:  rgb(34, 130, 175);
}
.box input[type = "submit"]{
  border:0;
  background: none;
  display: block;
  margin: 20px auto;
  text-align: center;
  border: 2px solid  rgb(34, 130, 175);
  padding: 10px 40px;
  outline: none;
  color: white;
  border-radius: 24px;
  transition: 0.25s;
  cursor: pointer;
   font-size: 16px;
}
.box input[type = "submit"]:hover{
  background:  rgb(34, 130, 175);
}
 
li a{
	text-decoration: none;
	color: rgb(255, 255, 255);
	font-weight: lighter;
	padding: 0 40px;
 
}

li{
 list-style: none;
}


</style>
